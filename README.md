# Control and Automation in Python
Examples of applications realated to control and automation using the Python Control Systems Library (python-control).

[Link to package documentation](https://python-control.readthedocs.io/en/0.9.0/)

## Stability Analisys

With respect to control theory, stability analysis is used to study and predict the stability or instability characteristics of a system from a knowledge of the mathematical model.

For this case it was used the Routh–Hurwitz stability criterion and Nyquist stability criterion.

### Nyquist Plot
![nyquist](https://user-images.githubusercontent.com/45636618/125877475-3f2e377d-0ca1-4270-ae40-a90ea9ba0589.jpg)


## Ziegler-Nichols Tuning method

The Ziegler-Nichols rule is a heuristic PID tuning rule that attempts to produce good values for the three PID gain parameters given two measured feedback loop parameters derived from measurements.

Below it is represented the open-loop step response of the analised system before (blue) and after (black) the method is aplied.

![ZN](https://user-images.githubusercontent.com/45636618/129389144-06a7d178-8684-4b3c-974c-f03bae63bf28.png)

