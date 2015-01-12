tcpstates
--------------------------------------------------------------------------------

Count of main TCP states and prints output as a chosen format (xml, json, key: value)

Format Output
--------------------------------------------------------------------------------

Just edit the script and set the "outputformat" variable as a chosen format.


Format Output Examples.

JSON:

	{ "tcpstates": [
        	{"timestamp": 1234567890},
	        {"listen": 0},
        	{"syn_sent": 0},
	        {"syn_received": 0},
        	{"established": 1},
	        {"close_wait": 0},
        	{"time_wait": 0}
	]}

XML:

	<?xml version="1.0" encoding="UTF-8"?>
        	<tcpstates>
                	<timestamp>1234567890</timestamp>
	                <syn_sent>0</syn_sent>
        		<syn_received>0</syn_received>
		        <established>1</established>
        		<close_wait>0</close_wait>
        		<time_wait>0</time_wait>
        	</tcpstates>
Key Value:

	listen 0 syn_sent 0 syn_reveiced 0 established 1 close_wait 0 time_wait 0
