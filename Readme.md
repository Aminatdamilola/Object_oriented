# Object-Oriented Programming: Gaussian & Binomial Distributions python package   

## 📌 Overview  
This project demonstrates Object-Oriented Programming (OOP) concepts by implementing **Gaussian** and **Binomial** distributions in Python. The classes allow users to compute probabilities, visualize distributions, and perform statistical operations.  

## 🚀 Features  
- Create and manipulate **Gaussian** and **Binomial** distributions  
- Compute **mean, variance, standard deviation**  
- Generate random samples  
- **Visualize distributions** with histograms and probability density functions  

## 📂 Project Structure  
- `Gaussian.py` – Implements Gaussian distribution  
- `Binomial.py` – Implements Binomial distribution  
- `README.md` – Project documentation  
 

## 📜 Usage  
### Gaussian Distribution  
```python
from Gaussian import Gaussian

gauss = Gaussian(mean=10, stdev=2)
print(gauss.mean, gauss.stdev)
gauss.plot_histogram()
