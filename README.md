# jmeter
This repo contains two of my more tricky jmeter tests. 
hld_pathways_v2.jmx consumes a csv file with multiple values and iterates through multiple assessments using the provided values, gets the results in the form of a "pathway" that is determined by logic from the client and compares them to the expected values. 

acceptable_foods_load_v2.jmx is a somewhat standard load test designed to target a specific area of a website that was performing slowly. This is run while monitoring the server for failures. 

Both of these tests are configured to use a local properties files so that secure values are not stored in the test. They cannot be run in their current state without that file. I am not at liberty to divulge that file or the csv that the pathways test consumes, but I felt like these were good examples of what I use jmeter for. 
