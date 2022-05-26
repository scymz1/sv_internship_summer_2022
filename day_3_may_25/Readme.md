
1. Record and recap the github commits to the Notebooks repositories
	1. [API documentation (Lize)](https://github.com/rice-crc/voyages-api/pull/33)
	1. [Map data](https://github.com/JohnMulligan/voyages_python_notebooks/pull/1)
	1. [Pivot tables (Haoyu)](https://github.com/JohnMulligan/voyages_python_notebooks/pull/2)
	1. Suggestions for improvements on the API (waiting on this, jcm10)
		1. Accept API requests with trailing slashes (and then update documentation)
		1. Selected Fields is required on the cache request (and i will change that, then we update the documentation)
		1. Errors logged Tuesday, especially pertaining to the groupby functions
1. Github:
	1. SSH authentication
	1. Fork + PR workflow
1. Move on to [John's Plotly apps](https://github.com/JohnMulligan/voyages_plotly_2022)
	1. git clone 
1. Review the django dataframes --> flask indices workflow.
	1. Django dataframes queries allow easy access to any set of variables, but it's data-hungry
	1. Flask indices are extremely fast, but
		1. They are kind of a pain to set up
		1. It's possible they'll collectively become large enough to justify a different architecture


1. The rest of the day can be dedicated to
	1. Reading Plotly's documentation in concert with
	1. What we already know about the dataset and how it can be accessed
	1. Explaining how the interfaces work (having broken into teams of 2)
1. Thursday
	1. Morning: presentations of their findings on the different interfaces
	1. Afternoon: Dr. Domingues presents on the history of the project
	1. Balance of the day, before or after:
		1. deployment to Heroku (from individual git branches)
		1. env settings


1. Friday --> React tree for OPTIONS calls.

## Changes

* Because we installed Docker yesterday, today's installation of the Plotly app quickly focused on changing virtual environment settings
* We then deployed to Heroku before lunch
* In the afternoon, the group used the codebase in 3 ways
	* Reading and experimenting with the code in the plotly repo
	* Focusing on component generation (especially autocomplete functionality, which Alison appears to have dived into)
	* Building a single-page app from scratch (provided an [example](https://github.com/JohnMulligan/voyages_plotly_2022/blob/de319cc9136eeb094c82ed704249d3f321f74a67/example.py))