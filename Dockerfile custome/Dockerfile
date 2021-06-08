# Step 1 specify the base images


FROM alpaine

#Step 2 Download and install dependencies

RUN apk add --update redis

# Step 3 Setup the startup command

CMO ["redis-server"]
