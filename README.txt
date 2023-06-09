Pre-Requisites
To run the modified script, here are the prerequisites:

1. Python: Ensure that Python3.6 is installed on your system. You can download the latest version of Python from the official Python website (https://www.python.org/) and follow the installation instructions specific to your operating system.

2. Required Packages: Install the necessary Python packages by running the following command in your terminal or command prompt:
Eg: pip install requests

3. Configuration File: Create a JSON configuration file (config.json) with the following structure:

	{
    	"ingest_url": "https://fhq90909.live.dynatrace.com/api/v2/metrics/ingest",
    	"headers": {
        	"accept": "application/json; charset=utf-8",
        	"Authorization": "Api-Token dt0c01.***ZLWBABM***************V6IW.YVYXHGPEX64EB**************CMH6SQ5CO3x5ULAaAsMRC4EBICPUXQ2***",
        	"Content-Type": "text/plain; charset=utf-8"
    	}
	}

4. Domains File: Create a CSV file (domains.csv) with each line containing a domain name and URL separated by a comma. For example:
example.com, https://example.com
example.net, https://example.net

5. chmod a+x <path to the ssl_expiry_script_v1.1>/ssl_expiry_script_v1.1


Once you have fulfilled the prerequisites, you can execute the script by running the following command in your terminal or command prompt:
./<path to the ssl_expiry_script_v1.1>/ssl_expiry_script_v1.1 </path to>/config.json> </path to>/domains.csv
example : ./home/dist/ssl_expiry_script_v1.1 /home/config/config.json /home/config/domains.csv


