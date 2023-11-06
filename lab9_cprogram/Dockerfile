# Set the base image to use
FROM gcc:latest
# Copy the C program into the container
COPY one_main.c .
# Compile the C program
RUN gcc -o one_main one_main.c
# Set the command to run when the container starts
CMD ["./one_main"]