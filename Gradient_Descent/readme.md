🚀 What is Gradient Descent?
Gradient Descent is an optimization algorithm used to minimize a function by iteratively moving towards the lowest point of a loss function. In ML, it's used to optimize model parameters (like weights in neural networks) to minimize errors.

Imagine you're hiking down a mountain blindfolded, feeling the slope with your feet. You take small steps downhill, ensuring you don’t trip. That’s gradient descent—step by step, moving towards the minimum loss.


📌 Most Important Points .
1️⃣ Cost Function (Loss Function)
A mathematical function that tells how bad the model is performing.
Example: Mean Squared Error (MSE) in regression, Cross-Entropy Loss in classification.
2️⃣ Gradient (Slope)
The partial derivative of the cost function. It tells the direction and magnitude of change.
A high gradient means we are far from the minimum; a low gradient means we are close.
3️⃣ Learning Rate (α)
Controls the size of each step.
Too high → Overshoots the minimum (never converges).
Too low → Takes forever to converge.
4️⃣ Convergence
When the model reaches a point where updates are negligible, meaning it's at or near the minimum loss.

🏃‍♂️ Types of Gradient Descent
1️⃣ Batch Gradient Descent (BGD)
Uses the entire dataset to compute gradients.
✅ Stable convergence, good for convex functions.
❌ Slow for large datasets.
2️⃣ Stochastic Gradient Descent (SGD)
Updates the model using one random sample at a time.
✅ Faster updates, works well for online learning.
❌ High variance, can oscillate.
3️⃣ Mini-Batch Gradient Descent
Uses a small subset (mini-batch) of data to compute gradients.
✅ Balances speed and stability.
❌ Choosing batch size requires tuning.
