graph LR
A[Start] --> B{Capture Image with Smartphone App}
B --> C{Confirm Disease by Image Analysis?}
C -- Yes --> D[Rice Blast Detected - Recommend Treatment]
C -- No --> E{Measure Soil Temperature & Moisture}
E --> F{Abnormal Temperature or Moisture?}
F -- Yes --> G{Likely Disease - Recommend Further Testing}
F -- No --> H{Measure Soil pH & NPK Levels}
H --> I{Nutrient Deficiency or Imbalance?}
I -- Yes --> J{Likely Disease - Recommend Further Testing} |Rice Bacterial Leaf Blight or Brown Spot|
I -- No --> K[Nutrient Levels Normal - Monitor Field]
J --> L{Analyze Data for Bacterial Leaf Blight or Brown Spot}
L -- Yes --> M[Rice Bacterial Leaf Blight Detected - Recommend Treatment]
L -- No --> N[Rice Brown Spot Detected - Recommend Treatment]
K --> D[. (Healthy Rice)]
