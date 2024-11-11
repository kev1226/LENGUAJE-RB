# Use an official Ruby image as a base
FROM ruby:3.3

# Set the working directory inside the container
WORKDIR /app

# Copy the Gemfile and Gemfile.lock to the container
COPY Gemfile Gemfile.lock ./

# Install the dependencies
RUN bundle install

# Copy the rest of the application code to the container
COPY . .

# Expose port 8080
EXPOSE 8080

# Command to run the application
CMD ["ruby", "app.rb", "-o", "0.0.0.0"]
