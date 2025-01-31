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
```

Sentiment Analysis

```python
from runash_ai import RunAsh

runash = RunAsh()
data = runash.load_data('path/to/sentiment_data.csv')
model = runash.train_sentiment_model(data)
predictions = runash.predict_sentiment(model, new_text_data)
print(predictions)
```

Image Classification

```python
from runash_ai import RunAsh

runash = RunAsh()
images = runash.load_images('path/to/images')
model = runash.train_image_model(images)
predictions = runash.predict_image(model, new_images)
print(predictions)
```
