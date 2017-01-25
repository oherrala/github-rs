The github-rs library does not provide a way to listen for Webhooks from
GitHub. This is something that should be up to the end user in how they
want to handle these types of requests However, the library does provide
all of the JSON types used as part of the Webhooks API. You can use
these as the type to listen for from a Webhook and then act accordingly.
