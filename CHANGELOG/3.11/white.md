 * Move GTK client to [another repository](https://github.com/infobyte/faraday-client) to improve release times.
 * Fix formula injection vulnerability when exporting vulnerability data to CSV. This was considered a low impact vulnerability.
 * Remove "--ssl" parameter. Read SSL information from the config file.
 * Add OpenAPI autogenerated documentation support
 * Show agent information in command history
 * Add bulk delete endpoint for hosts API
 * Add column with information to track agent execution data
 * Add tool attribute to vulnerability to avoid incorrectly showing "Web UI" as creator tool
 * Add sorting by target in credentials view
 * Add creator information when uploading reports or using de bulk create api
 * Use run date instead of creation date when plugins report specifies it
 * Improve knowledge base UX
 * Sort results in count API endpoint
 * Limit description width in knowledge base
 * Change log date format to ISO 8601
 * Fix parsing server port config in server.ini
 * Fix bug when _rev was send to the hosts API
 * Send JSON response when you get a 500 or 404 error
 * Fix bug parsing invalid data in NullToBlankString