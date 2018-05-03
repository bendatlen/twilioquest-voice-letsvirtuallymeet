node.js application using Twilio to setup a Conference and setup a moderator using the request body From parameter to identify the caller by their number.  If the moderator number matches that of the caller the conference opens, if not the caller has to wait until the moderator joins the conference for it to begin.  This web server in this example uses port 1337 which can be changed in the code `http.createServer(app).listen(`**1337**`, () => {`

## Requirements
[NodeJS and NPM](http://nodejs.org/download)   

## Related modules
[twilio](https://www.npmjs.com/package/twilio) - Twilio helper library for node   
[express](https://github.com/visionmedia/express) - web application framework for node   
[body-parser](https://www.npmjs.com/package/body-parser) - Parse message request bodies   
[dotenv](https://www.npmjs.com/package/dot-env) - merges .env file into process.env runtime for using environment variables   

## License
None

