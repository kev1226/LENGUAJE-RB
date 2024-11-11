# Step 1: Clone the repository 

# Locate me on the LANGUAGE-RUBY cd termia

# Step 2: Build the Docker image
docker build -t ruby-docker .

# Step 3: Run the container
docker run -p 8080:8080 ruby-docker

# Note: The application will be accessible at http://localhost:8080