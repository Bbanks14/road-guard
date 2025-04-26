# Installation

## Prerequisites

- Python 3.8+
- Raspberry Pi (for hardware deployment)
- Compatible sensors (USB camera, infrared camera etc.)
- Git (for cloning the repository)

## Steps

- Clone the repository:

````bash
git clone https://github.com/your-username/road-guard.git
cd road-guard

* Install software dependencies:

```bash
pip install requirements.txt

* Set up hardware (if applicable):
  * Connect sensors to the processing unit as per HARDWARE_SETUP[../HARDWARE_SETUP.md].
  * Configure GPIO pins or USB interfaces for sensor communication.

* Configure environment variables:
  * Copy the .env.example(../.env.example) file to .env(../.env) file and update with your settings (e.g API keys, GPS coordinates).
  ```bash
  cp .env.example .env

  * Run the application:
  ```bash
  python src/main.py
````
