## Layer	Proposed Technology


Mobile App:	Flutter / React Native

Image Processing:	OpenCV

AI/Deep Learning:	PyTorch / TensorFlow

Object Detection / Classification:	Suitable CV architecture selected after evaluation

Backend:	FastAPI

Report Generation:	PDF generation module

Model Deployment:	"Cloud API initially; on-device optimization as future scope"

##

For the SIH proposal, I recommend keeping the approach model-independent so your team can change the AI architecture later based on accuracy, speed, and deployment requirements.

## Key Technical Innovation

AI prediction → measurable parameters → official grading rules → transparent quality report

The important distinction is that the AI model does not arbitrarily decide the final grade. It extracts measurable quality information, which is then evaluated by a standardized grading engine based on applicable official standards.

This makes the system more explainable, auditable, and adaptable if the grading rules or AI model change.
