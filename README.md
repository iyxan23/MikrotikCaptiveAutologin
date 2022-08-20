# Mikrotik Captive Autologin

This Node.js script automatically logs into [Mikrotik](https://mikrotik.com) captive portal.

## Configure

Create `config.json` inside the script folder, like this:

```json
[
    {
        "ssid": "<wifi name>",
        "hostname": "<captive portal hostname without http://>",
        "username": "<your username>",
        "password": "<your password>"
    }
]
```

You can add multiple configurations for different SSIDs.

Install the dependencies.

    npm install

Then run this script.

    npm run start

## Contributors

Thank you so much to [Iyxan23](https://github.com/Iyxan23) for the idea and helping me out in a lot of things,
since my JavaScript and Node.js knowledge is a bit rusty (pun intended).

## License

This script is licensed under the MIT License, except the MD5 encoder (`md5.js`).

The MD5 encoder is licensed under the BSD License, © 1998-2009 Paul Johnston & Contributors.