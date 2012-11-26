TO DO

- c/p the dropdown menu from request to response. Responders should select a location, and send a string to the server
which reads `Response:Help Team X|[LOCATION]`

- Server should now take `[PORT NUMBER] [QUEUEING METHOD]`. If the queueing method is incorrect or does not exist, the server should exit. The message to the requester should be `Assigned:Help Team X. Time to your location is approximately Y minute(s).` The message to the responder should read `Assigned:[LOCATION] - [URGENCY]`
