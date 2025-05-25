# aias-backend

## Project Setup

### Step 1: Set up Virtual Environment

-   **For Windows:**

    ```bash
    python -m venv venv
    venv\Scripts\activate
    ```

-   **For macOS/Linux:**
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

### Step 2: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 3: Set up .env file

-   **For Windows:**

    ```bash
    copy .env.example .env
    ```

-   **For macOS/Linux:**
    ```bash
    cp .env.example .env
    ```

### Step 4: Run the Backend

```bash
python run.py
```

### [Optional]: Deactivate the Virtual Environment

To deactivate the virtual environment:

```bash
deactivate
```

---

### [Optional]: Update requirements.txt file

```bash
pip freeze > requirements.txt
```
