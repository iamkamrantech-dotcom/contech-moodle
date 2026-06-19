# Contech International - Moodle LMS

## Overview

This repository contains the Moodle Learning Management System (LMS) setup for Contech International.

---

## Installation

### 1. Clone the Moodle Repository

Run the following command to download the Moodle source code:

```bash
git clone -b MOODLE_404_STABLE https://github.com/moodle/moodle.git html
```

### 2. Start the Docker Environment

Launch the required containers using Docker Compose:

```bash
docker compose up -d
```

### 3. Access the Application

Once the containers are running, open your browser and navigate to:

```
http://localhost:8080
```

---

## Administrator Access

Use the following credentials to sign in to the Moodle admin panel:

**Email:** [admin@contech.com](mailto:admin@contech.com)

**Password:** *Use the password configured during setup.*

---

## Requirements

* Docker
* Docker Compose
* Git

---

## Support

If you encounter any issues during installation or setup, please contact the Contech International technical team for assistance.
