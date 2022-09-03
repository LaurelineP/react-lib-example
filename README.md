# REACT LIB EXAMPLE

## DEVELOPMENT ENVIRONMENT
In development environment it is recommended to take into account the following:
- create a library or a standalone ? *--> library for this project*
- environment options ? *--> CRA for this project*
	- starting with a boilerplate ? pick the right one [ a lot of them - 2 recommended : CRA and NWB ]
	- starting with a documentation styled tool [ styleguidist, style guide generator , cosmos, atelier,bluekit ]
	- starting from scratch ? 

- **Installation**
	- Node ( + npm ): https://nodejs.org/api/https.html
	- CRA: `npx create-react-app <PROJECT RELATIVE PATH>`
- **Eject CRA**
	- CRA benefits from the boilerplate updates
	- CRA abstract away all dependencies and configuration  
	We can observe a different from all the dependencies 
	within node_modules and what is declared within `package.json`
	Ejecting will allow more customization for the project
	`npm run eject`
	- CRA ejected:
		- ability to see all dependencies ( previously abstracted away )
		- ability to see config folder
		- ability to see script folder
	- Clean project development environment: as it is not an app but a library
		- Delete:
			-  `src/logo.svg` ✗ its import in `App.js`
			-  `src/App.css` ✗ its import in `App.js`
			-  in `src/App.js`: remove unnecessary jsx