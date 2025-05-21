# spotify-image-gen

File org:

album_cover_app/
├── app/
│   ├── __init__.py              # Initialize Flask app
│   ├── routes.py                # Define app routes
│   ├── templates/
│   │   └── index.html           # UI (upload form, results, etc.)
│   ├── static/
│   │   └── style.css            # Optional CSS styling
│   ├── model/
│   │   ├── model.py             # Load + run the pretrained model
│   │   └── model_weights/       # Your pretrained model files (e.g., .pt, .h5, etc.)
│   └── utils/
│       └── image_utils.py       # Image preprocessing/postprocessing
├── requirements.txt
├── run.py                       # Run the Flask server
└── README.md
