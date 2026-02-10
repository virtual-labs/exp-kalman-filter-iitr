#### Please attempt the following questions

<br>
Q1. What is the consequence of setting the initial state covariance too high in the Kalman filter?<br>
a. The filter converges quickly but may be inaccurate <br>
b. The filter converges slowly but robustly <br>
c. The filter ignores new measurements <br>
d. The filter does not converge at all <br>

<br>
Q2. What is the effect of choosing an initial state covariance that is too low?<br>
a. The filter will ignore all measurements <br>
b. The filter will adapt quickly to measurements but might be less robust <br>
c. The filter will converge very slowly <br>
d. The filter will become unstable <br>

<br>
Q3. How can initial conditions of the Kalman filter be optimized for better prediction performance?<br>
a. By setting all initial values to zero <br>
b. By guessing the initial values <br>
c. By using domain knowledge and historical data <br>
d. By not initializing them at all <br>

<br>
Q4. In the Kalman filter simulation, what is the initial state estimate represented by?<br>
a. A <br>
b. x0 <br>
c. num_steps <br>
d. x0_est <br>

<br>
Q5. In the absence of process noise, how does the Kalman filter primarily account for uncertainties in the state estimates?<br>
a. Through the state transition matrix <br>
b. By adjusting the measurement noise variance <br>
c. By updating the error covariance matrix using the Kalman gain <br>
d. By modifying the initial state estimate <br>

<br>
Q6. Can the initial state estimate (x0_est) be changed, and what effect does it have on the Kalman filter simulation?<br>
a. No, it must always be [0; 0] <br>
b. Yes, it can be changed, and it affects the initial convergence and accuracy of the filter <br>
c. No, changing it will cause the filter to fail <br>
d. Yes, it can be changed, but it has no effect on the simulation <br>

<br>
Q7. What is the main observation about the estimated state (x0_est) compared to the true state (x0) for State 1 over time? (From the figure)<br>
a. The estimated state diverges significantly from the true state <br>
b. The estimated state closely follows the true state <br>
c. The estimated state fluctuates widely around the true state <br>
d. The estimated state remains constant while the true state changes <br>

<br>
Q8. What can be inferred about the behaviour of State 2 from the simulation results? (From the figure)<br>
a. State 2 is decreasing over time <br>
b. State 2 remains constant after an initial change <br>
c. State 2 oscillates significantly <br>
d. State 2 shows an exponential growth <br>

<br>
Q9. What is the role of the Kalman gain in the Kalman filter?<br>
a. It determines the process noise covariance <br>
b. It balances the trust between model prediction and measurement <br>
c. It initializes the state vector <br>
d. It defines the system dynamics <br>

<br>
Q10. What happens if the measurement noise covariance is increased in a Kalman filter?<br>
a. The filter relies more on measurements <br>
b. The filter relies more on the model prediction <br>
c. The filter becomes unstable <br>
d. The filter ignores the state transition model <br>

<br>