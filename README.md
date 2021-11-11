# alphasense
 - To start test
	 - Install Jmeter.
	 - To open the script in edit mode run the following command in terminal <pathtojmeter>bin/jmeter -t AlphaSense-Assignment.jmx
	 - To start a test using default setting run following command in terminal <pathtojmeter>bin/jmeter -n -t 	 -AlphaSense-Assignment.jmx -l Run1.jtl -e -o Run1-1000U-Prod
	 - To view report open index.html from folder Run1-1000U-Prod

- Below is the default setting of the test script
	 - Environment=Prod
	 - Total Users=1000
	 - Ramp up duration=15
	 - Test duration=600 secs
