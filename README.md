To successfully run this full-stack application, which consists of a Django backend and a Next.js frontend, follow the steps outlined below. This guide assumes you have Python and Node.js installed on your system.

## Backend Setup (Django)

1. **Clone the project repository**:
   Open a terminal and clone the project using the following command.
   ```sh
   git clone https://github.com/Seyamalam/fullstack_django_next_resturant_menu.git
   ```

2. **Navigate to the project root directory**:
   Change to the project directory.
   ```sh
   cd fullstack_django_next_resturant_menu
   ```

3. **Create and activate a virtual environment**:
   - For Windows:
     ```sh
     python -m venv venv
     .\venv\Scripts\activate
     ```
   - For macOS/Linux:
     ```sh
     python3 -m venv venv
     source venv/bin/activate
     ```

4. **Install the required Python packages**:
   ```sh
   pip install -r requirements.txt
   ```

5. **Run migrations to set up your database**:
   ```sh
   python manage.py migrate
   ```

6. **Start the Django development server**:
   ```sh
   python manage.py runserver
   ```
   The Django server will start running on `http://127.0.0.1:8000/`.

## Frontend Setup (Next.js)

1. **Navigate to the Next.js project directory**:
   ```sh
   cd next-js-front
   ```

2. **Install the required Node.js packages**:
   ```sh
   npm install
   ```

3. **Start the Next.js development server**:
   ```sh
   npm run dev
   ```
   The Next.js server will start running on `http://localhost:3000/`.

## Accessing the Application

- Open your web browser and navigate to `http://localhost:3000/` to view the frontend.
- The backend API can be accessed via `http://127.0.0.1:8000/`.


