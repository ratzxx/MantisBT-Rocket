MantisBT-Rocket
==============

A [MantisBT](http://www.mantisbt.org/) plugin to send bug updates to [RocketChat](https://rocket.chat/) channels.


# Setup
* Extract this repo to your *Mantis folder/plugins/Rocket*.
* On the RocketChat side, add a new "Incoming Webhooks" integration and note the URL that Slack generates for you.
* On the MantisBT side, access the plugin's configuration page and fill in your RocketChat webhook URL.
* You can specify which bug fields appear in the RocketChat notifications. Edit the *plugin_Rocket_columns* configuration option for this purpose.  Follow the instructions on the plugin configuration page.

Thanks to [Karim Ratib](https://github.com/infojunkie) for MantisBT-Slack
