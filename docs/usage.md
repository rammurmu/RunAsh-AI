# Usage

## Basic Example

Here is a basic example of how to use RunAsh AI:

```python
from runash_ai import RunAsh

# Initialize the RunAsh AI module
runash = RunAsh()

# Load data
data = runash.load_data('path/to/your/data.csv')

# Train the model
model = runash.train_model(data)

# Make predictions
predictions = runash.predict(model, new_data)
print(predictions)
