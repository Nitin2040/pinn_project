# 🔬 PINN Burgers' Equation Solver
This Streamlit web app compares the Physics-Informed Neural Network (PINN) prediction with the analytical solution of the 1D Burgers' Equation on a predefined domain.

# 🧠 About
Solves the Burgers' equation using a pretrained PINN model.

Accepts user-defined values for time t and space x.

Displays both the PINN-predicted and analytically computed solution.

Computes and shows the absolute error between the two.

(Optional) Supports plotting 
𝑢(𝑥)
u(x) for a fixed time 
𝑡.

# 📦 Requirements
Install the necessary Python packages:

bash
Copy
Edit
pip install streamlit numpy tensorflow
If you wish to enable plotting:

bash
Copy
Edit
pip install matplotlib
