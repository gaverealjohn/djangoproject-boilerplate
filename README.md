# Django Project Boilerplate

#### To start development:
1. Create and activate virtual environment (win: py -m vevn [env]).
2. Install requirements (py -m pip install -r requirememts.txt).
3. Create .env file in the project rood directory and add the secret key and other info like database namae (SECRET_KEY=[your_secret_key_without_any_space]).
4. Rename project. Run 'py manage.py rename [new_project_name]'
5. Create 'static_in_env' folder in the project directory then run 'py manage.py collectstatic'.
6. Run 'py manage.py migrate' then 'py manage.py runserver' to check if your project is working.
