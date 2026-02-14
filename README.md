# my-project-2

A minimal Python application scaffold.

## Structure

```
my-project-2/
├── app/
│   └── main.py      # Main application entry point
├── requirements.txt  # Python dependencies
├── Dockerfile       # Container configuration
└── README.md        # This file
```

## Running Locally

```bash
python app/main.py
```

## Running with Docker

```bash
docker build -t my-project-2 .
docker run my-project-2
```

## Development

Add your Python dependencies to `requirements.txt` and install them:

```bash
pip install -r requirements.txt
```
