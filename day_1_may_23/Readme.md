* Run the class on zoom
* Everyone logs in
* Can share screens as needed/instructional

1. Group & individual introductions
	1. Structure of the OIT CRC Internship program, and some past projects
	1. Academic concentrations, professional goals, and personal goals for the program
1. Project goals
	1. To understand
		1. The SlaveVoyages database
		1. Public uses of it
		1. Scholarly uses of it
		1. Emerging uses by programmers
	1. To
		1. Learn to use a new API that makes the data generally available
		1. Build front-end React components that use the api
		1. Fold these components together into interfaces
		1. Iterate the API on the basis of these new requests
		1. Deploy the front-ends to the cloud in a CD pipeline
		1. Iterate on the basis of feedback from the scholars
		1. Finish the summer with a working prototype of a new site
1. Introduction to [SlaveVoyages.org](https://www.slavevoyages.org/)
	1. Voyages
	1. People
		1. Named
		1. Unnamed
	1. Places
	1. Sources
	1. queries (& saved queries!)
	1. results
		1. tables & cards (list view)
		1. visualizations & pivot tables (statistical)
		1. maps (node-based visualization)
1. Current state
	1. Cloud infrastructure deployment [DIAGRAM](djk_voyages_oci_deployment.png) (increasing deployment tempo, mitigates against the below:)
	1. App server model [DIAGRAM](voyages_app_current_state_sketch_only.pdf)
		1. highly-customized functionality
		1. highly fragile
1. Future state [DIAGRAM](jcm_voyages_api.pdf)
	1. API model (separates database, API, and front-end interfaces)
	1. How it works under the hood anyways :)
	1. How to make requests
		1. Grant everyone an API key
		1. Have everyone install [Postman](https://www.postman.com/) & set it up
		1. Have everyone launch a python virtual environment
		1. Using Python and Postman, reproduce all the queries in the [API documentation](https://github.com/rice-crc/voyages-api)