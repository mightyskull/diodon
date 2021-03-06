# Diodon
Aiming to be the best integrated clipboard manager for the Unity desktop.

## Installing

For Ubuntu based distributes there is an official [stable PPA](https://launchpad.net/~diodon-team/+archive/stable).

    sudo add-apt-repository ppa:diodon-team/stable
    sudo apt-get update
    sudo apt-get install -y diodon


To install Diodon on other systems download a release tarball from [launchpad](https://launchpad.net/diodon/+download).

## Building

Diodon uses the [waf](https://waf.io) build system.

    git clone https://github.com/diodon-dev/diodon.git
    cd diodon
    ./waf configure
    ./waf build
    sudo ./waf install

## Plugins

If you would like to write your own Diodon plugin please refer to [the original blog post](http://esite.ch/2011/10/19/writing-a-plugin-for-diodon/). Feel free to add your own plugins to the list below.

|  Plugin                                                  | Description                                        |
| -------------------------------------------------------- | -------------------------------------------------- |
| [Features](https://github.com/RedHatter/diodon-plugins)  | Additional features for the diodon menu.           |
| [Numbers](https://github.com/RedHatter/diodon-plugins)   | Number clipboard menu items.                       |
| [Pop Item](https://github.com/RedHatter/diodon-plugins)  | Pastes and then removes the active clipboard item. |
| [Paste All](https://github.com/RedHatter/diodon-plugins) | Paste all recent items at once                     |
| [Edit](https://github.com/RedHatter/diodon-plugins)      | Prompts to edit the active item.                   |

## Support

Take part in the discussion or report a bug on the [launchpad](https://bugs.launchpad.net/diodon) page.

Join us in #diodon on irc.freenode.net if you want to get involved or need any help.
