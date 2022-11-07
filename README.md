# Example_Percy_API

-   Identify your Percy Project Token from the Project Settings and export them as environment variables using the below commands.
-   Note: The PERCY_TOKEN must be either Read-only or Full-access. Refer this [document](https://docs.percy.io/reference/authentication).
    -   For \*nix based and Mac machines:

    ```sh
    export PERCY_TOKEN=<percy-token>
    ```

    -   For Windows:

    ```shell
    set PERCY_TOKEN=<percy-token>
    ```
-   Install dependencies `pip install -r requirements.txt`
-   To run the script use `python3 percy_api.py <project_slug>
