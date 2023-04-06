### ARG

ARG is used to supply some variables at the time of image creation
ARG is only instruction is used before the FROM instruction . It cant used after FROM instruction.
### Diffrence between ARG and ENV.
- ANS: ARG instruction is used at the time of image creation . ENV is used for both image and container creation.
### Using ENV and ARG for best results.
- Create one ENV variable and assign the value to ARG to that .
- Then we can access ARG values through ENV both image and container.
