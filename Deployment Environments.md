Here we go over each revelant category in deployment that may or may not be applicable to your product. Look at each header and first paragraph line(s) to see if it's applicable.

# Pipelines
Modern development should follow a TDD (test driven development) structure. Pipelines are crucial for this as they make sure that what you just developed hasn't broken anything that was already in place. You don't want to waste time checking things you've already checked before, so write tests once, setup a pipeline once, and execute them on every commit.

# Hosting
If you're developing a server-client structure, assess how much traffic the server will be getting and who will be using it. This helps determine whether to host it on-premises or in the cloud.

Internal apps are more secure if they're hosted on-premises but external apps are more secure if the endpoints are on the cloud.

# Telemetry
If what you're developing is something you'll be bound to maintain and continue running (even if it's not a server), it's very important to develop it with enough telemetry and alerts so that when anything goes wrong you already know what went wrong, when and why.
