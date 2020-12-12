FROM ros:kinetic

RUN apt update && apt install -y git python-pip python-serial python-qt4 ros-kinetic-joystick-drivers ros-kinetic-xacro ros-kinetic-control-msgs
RUN pip install git+https://github.com/SAKErobotics/libezgripper.git#egg=libezgripper
CMD [ "bash" ]