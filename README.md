# MECH 529: Advanced Mechanical Systems - Lab Materials

Interactive lab materials and tutorials for MECH 529: Advanced Mechanical Systems at Colorado State University.

## 📚 View the Book

**Access the published book online**: [MECH 529 Lab Materials](https://labs.jianguozhaorobotics.com)

The site is automatically built and deployed using GitHub Actions whenever changes are pushed to the main branch.

## 🚀 Building Locally

To build the MyST book locally:

1. **Install dependencies**:
```bash
pip install -r requirements.txt
```

2. **Build the book**:
```bash
myst build --html
```

3. **View the book**: Open `_build/site/index.html` in your browser or run a local server

## 📖 Course Content

This course includes 11 interactive labs covering:

1. **Python Basics** - Python fundamentals, NumPy, Matplotlib
2. **ODEs** - Solving ordinary differential equations numerically
3. **Intro to Python Control** - Control systems with `python-control`
4. **Closed Loop Control** - Feedback control system design
5. **LQR** - Linear Quadratic Regulator optimization
6. **Trajectory Tracking** - Path planning and tracking control
7. **Trajectory Generation** - Smooth trajectory generation
8. **Model Predictive Control** - MPC formulation and implementation
9. **Value & Policy Iteration** - Dynamic programming methods
10. **Reinforcement Learning** - Q-learning and neural networks
11. **Final Project: Acrobot** - Control of underactuated systems

## 🛠️ Technologies

- [MyST Markdown](https://mystmd.org/) - Modern scientific publishing
- [Python](https://www.python.org/) with scientific computing libraries
- [Jupyter Notebooks](https://jupyter.org/) - Interactive computing
- [GitHub Actions](https://github.com/features/actions) - Automated CI/CD

## 📝 Requirements

See `requirements.txt` for all dependencies. Key packages:
- numpy
- scipy
- matplotlib
- ipython
- jupyter
- control (python-control)
- scikit-learn

## 👨‍🏫 Instructor

**Prof. Jianguo Zhao**
- Department of Mechanical Engineering
- Colorado State University
- Email: zhao@colostate.edu
- Lab: Adaptive Robotics Lab

## 📄 License

Educational materials - See LICENSE file for details.

---

*Last Updated: January 2026*
