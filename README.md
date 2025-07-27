# Get Together

A simple political events platform built with Flask. It allows organisers to post canvassing sessions, fundraisers, and other events. Users can search events by location and see them in chronological order. The interface is styled in dark mode with a card layout.

## Setup

Create a virtual environment and install dependencies:

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

Initialise the database (you may need to recreate it if upgrading from an
earlier version):

```bash
python -c 'from app import db; db.create_all()'
```

Run the server:

```bash
flask run
```

## Features

- Personal and organiser accounts
- Create and list events by location
- Chronological timeline of upcoming events
- Simple location search to find events near you
- Optional home location on your profile to automatically suggest nearby events

This is only a minimal prototype and does not include production security or a full feature set.
