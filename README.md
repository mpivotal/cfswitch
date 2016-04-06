# cfswitch
Enables quick account switching between different Cloud Foundry environments.

```$ cfswitch <CF ACCOUNT>```

![alt tag](https://raw.githubusercontent.com/mpivotal/cfswitch/master/using_cfswitch.gif)

## Install
```cfswitch``` is a simple shell script and how you install it is entirely up to you. Just remember to ```chmod +x``` to make it executable.

```$ mkdir ~/workspace```

```$ cd ~/workspace```

```$ git clone https://github.com/mpivotal/cfswitch.git```

```$ ln -s ~/workspace/cfswitch/cfswitch /usr/local/bin/cfswitch```

```$ chmod +x /usr/local/bin/cfswitch```

```$ cfswitch default```

Follow the instructions provided about how to create your initial account that ```cfswitch``` can help you quickly switch to.
