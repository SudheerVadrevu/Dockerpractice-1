ARG version
FROM almalinux:${version:-8}  
ARG sudheer=funnyboy
ARG vineela=lazygirl
RUN echo "sudheer is ${sudheer} vineela is ${vineela} "
CMD ["sleep", "100"]








# Above syntax given in FROM used only for version in ARG. Outside ARG that syntax not needed
# If user not given version in run time then by default it takes version -8

# How do you check your OS version? cat /etc/*release