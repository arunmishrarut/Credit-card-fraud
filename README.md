
# ⚡ Model-Driven Oversampling for Fraud Detection
This repository showcases a novel, math-driven, and original oversampling strategy for imbalanced credit card fraud detection—outperforming all standard projects and benchmarks!

🚀 Key Highlights
**Mathematical Innovation**: Hard-to-classify cases are detected using a custom scoring formula based on model prediction probabilities.

**Custom Oversampling**: Dynamically amplifies the hardest fraud and legitimate samples, not just the rare ones.

**Adaptive Lambda Tuning**: Intelligently balances class ratios without ballooning dataset size.

**Benchmarking**: Surpasses Baseline, SMOTE, ADASYN, and TabNet—see the notebook for results!

**No Data Leakage**: Test set is strictly held out for honest evaluation.


Samples with the highest scores are prioritized for oversampling, ensuring the main model focuses on its biggest weaknesses.

# 🛠️ Tech Stack
Python, Pandas, NumPy, Matplotlib

scikit-learn, imbalanced-learn

XGBoost

PyTorch TabNet

# 💡 What I Learned
**Math-driven modeling**: It is everything. Focusing on the hardest samples (by prediction error) delivers far better generalization than generic oversampling.

**Originality**: I won’t shy away from saying I felt elated by what I built. After hundreds of iterations,reading research papers, and over 100+ hours on Google Colab GPU runtime, it was all truly worth it.

**Smart oversampling > brute force**: Adaptive, model-aware duplication creates robust, production-ready fraud detectors.

Runtime: ~5 min on GPU | ~15 hrs on CPU
