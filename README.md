# Tool Test

A test repository for demonstrating Python development tools and workflows

### Prerequisites

 - `Python`
 - `Docker`

## Project Setup

```bash
python3 -m venv venv
```

```bash
source venv/bin/activate
```

```bash
# Install dependencies
pip install -r requirements.txt
```

## Usage

```bash
# Run script
python app.py
```

### with Docker

```bash
# Build image
docker build -t app-image:1.0.0 .
```

```bash
# Run container
docker run --rm -d app-image:1.0.0
```

## Project Structure

- `app.py`: Main application file
- `requirements.txt`: Python dependencies
- `Dockerfile`
- `.env.copy`: Copy of .env file; Create .env file and paste content from the .env.copy

