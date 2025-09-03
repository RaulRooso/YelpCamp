`app.all(/(.*)/, (req, res, next) => {`  <- Needed when getting an error like this: 'throw new TypeError(`Missing parameter name at ${i}: ${DEBUG_URL}`);
TypeError: Missing parameter name at 1: https://git.new/pathToRegexpError'
changed "if (util.isArray(msg)) {" with "if (Array.isArray(msg)) {" in connect-flash package because it had deprecation error