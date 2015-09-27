# folding-at-home
Docker definition for folding-at-home w/ external config.xml

Inspired by others, but everyone had their config.xml's hardbuilt inside the docker image.

Use this like so:
<pre>docker run -d -v <path_to_config_xml>:/config:ro bwooce/folding-at-home</pre>

Add a -i if you'd like to see what's going on/wrong.
