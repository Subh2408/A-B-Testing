# A/B Test Analyzer (Frequentist vs Bayesian)

An interactive A/B testing simulator that compares results using both **Frequentist** and **Bayesian** approaches.  
Provides statistical outputs, probabilities, and a clear final recommendation based on your input data.

---

## 🚀 Features
- **Input Variants**: Set users and conversions for Variant A (Control) and Variant B (Treatment).
- **Significance Level**: Choose your desired α (e.g., 0.05 for 95% confidence).
- **Test Types**: Supports both two-tailed and one-tailed tests.
- **Frequentist Analysis**: Calculates z-scores, p-values, and statistical significance.
- **Bayesian Analysis**: Provides posterior probabilities and Bayesian conclusions.
- **Final Recommendation**: Clear indication whether Variant B outperforms Variant A.
- **Recent Tests Log**: Easily track previous runs during a session.
- **Light/Dark Mode**: Toggle between themes for better accessibility.

---

## 📚 How It Works
1. **Input your data**: Users and conversions for both variants.
2. **Set significance level**: (Default is 0.05, meaning 95% confidence).
3. **Choose test type**: Two-tailed (detect any difference) or One-tailed (B > A).
4. **Run Analysis**: View both Frequentist and Bayesian results side-by-side.
5. **Get Recommendation**: Understand if the result is statistically significant and which variant is better.

---

## 🖥️ Deployment
The project is live!  
https://a-b-testing-fx6y.onrender.com


---

## 🧠 About A/B Testing Approaches

**Frequentist Testing**  
Calculates the probability of observing the data (or something more extreme) assuming the null hypothesis is true.  
Gives p-values and z-scores.  
Declares significance based on threshold (like 0.05).

**Bayesian Testing**  
Updates beliefs based on observed data.  
Directly provides probability of Variant B being better than Variant A (P(B>A)).  
No need for p-values; focuses on probability estimates.

---
