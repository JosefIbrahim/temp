{
    "builders": [
        {
            "type": "googlecompute",
            "project_id": "coen-josef-ibrahim",
            "image_name": "sandbox-{{timestamp}}",
            "image_family" : "wordpress-images",
            "source_image": "ubuntu-2004-focal-v20200720",
            "ssh_username": "packer",
            "zone": "europe-west3-a"
        }
    ],
    "provisioners": [
        {
            "type": "shell",
            "script": "packer.sh"
        }
    ]
}
