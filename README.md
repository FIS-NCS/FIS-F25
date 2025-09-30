# Lab 6 - Digital Forensics

1. Ensure you have docker and docker compose installed

    ```bash
    docker -v
    docker compose version
    ```

2. Clone this repo

    ```bash
    git clone https://github.com/FIS-F25/lab6
    ```

3. Change into the project directory

    ```bash
    cd lab6
    ```

4. Fix permissions of the recordings directory if needed

    ```bash
    sudo chmod 777 recordings
    ```

5. Stop previous labs (if any)

    ```bash
    docker kill terminal renderer nginx
    docker container prune -f
    ```

6. Run the lab:

    ```bash
    docker compose pull
    docker compose up -d
    ```

7. Access the lab at <http://localhost:8080>
