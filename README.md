Q2Online OSX Launcher
--

[Q2Online](http://q2online.net/action) launcher, build it or download it.


# Downloading it

Just download from the [releases](https://github.com/AQ2Chile/q2online-osx/releases) tab.

Copy the contents of the `bundle` folder into your `Applications` folder.

## Building it

1. Download and install [jar2app](https://github.com/Jorl17/jar2app)
2. Clone this project
    ```bash
        git clone git@github.com:AQ2Chile/q2online-osx.git
        cd q2online-osx/src
    ```
3. Build it
    ```bash
        jar2app q2online-client.jar ../bundle/Q2Online -i macicon.icns
    ```
4. Copy Q2Online.app to your `Applications` folder
5. Run it
6. Frag some shit

