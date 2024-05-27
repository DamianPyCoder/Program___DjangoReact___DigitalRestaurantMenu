<a name="readme-top"></a>

![](https://github.com/DamianPyCoder/DamianPyCoder/blob/main/canvas/damialicious.png)



## 1. Description.


<p align="right">(<a href="#readme-top">back to top</a>)</p>


## 2. Built with.

https://github.com/DamianPyCoder/RandomAssets__icons__V2/blob/main/React-Dark.svg


<p align="right">(<a href="#readme-top">back to top</a>)</p>



## 3. Development Roadmap.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 4. Typography, Colors, Icons and Other Elements.  

### 4.1 Icons.
<img src="https://github.com/DamianPyCoder/Program___DjangoReact___DigitalRestaurantMenu/blob/main/picts/menu.png" width="50">  <img src="https://github.com/DamianPyCoder/Program___DjangoReact___DigitalRestaurantMenu/blob/main/picts/menu1.png" width="50">  <img src="https://github.com/DamianPyCoder/Program___DjangoReact___DigitalRestaurantMenu/blob/main/picts/menu2.png" width="50">  <img src="https://github.com/DamianPyCoder/Program___DjangoReact___DigitalRestaurantMenu/blob/main/picts/menu2B.png" width="50">  <img src="https://github.com/DamianPyCoder/Program___DjangoReact___DigitalRestaurantMenu/blob/main/picts/menuB.png" width="50">  
Source of the icon: [Freepik](https://www.flaticon.es/icono-gratis/menu_1046747)  




<p align="right">(<a href="#readme-top">back to top</a>)</p>





## 5. Images and Videos.


<p align="right">(<a href="#readme-top">back to top</a>)</p>



## 6. How to download the Django and React repository.


**Set up the Django environment (Backend):**  

Make sure you have Python and pip installed on your computer.
Navigate to the backend directory (probably a folder named `backend` or something similar) and create a virtual environment:  

      python -m venv env
        
Activate the virtual environment:
On Windows:        

      .\env\Scripts\activate 
        
On macOS/Linux:

      source env/bin/activate
       
Install the backend dependencies:

      pip install -r requirements.txt

Apply database migrations:

      python manage.py migrate
 
Run the Django development server:

      python manage.py runserver

**Set up the React environment (Frontend):**  

Make sure you have Node.js and npm (or yarn) installed on your computer.
Navigate to the frontend directory (probably a folder named `frontend` or something similar).
Install the frontend dependencies:  
    
With npm:

      npm install
        
With yarn:

      yarn install 
        
Start the React development server:  
With npm:

      npm start
        
With yarn:

      yarn start


**Configure CORS (Cross-Origin Resource Sharing):**  

If your frontend and backend are on different ports (e.g., backend on port 8000 and frontend on port 3000), you need to ensure the backend allows requests from the frontend.
Install `django-cors-headers` in the backend virtual environment: 

      pip install django-cors-headers
      
Add `corsheaders` to the list of installed apps in `settings.py` of Django:

      INSTALLED_APPS = [
          ...
          'corsheaders',
          ...
      ] 
      
Add the CORS middleware in `settings.py`:

      MIDDLEWARE = [
          ...
          'corsheaders.middleware.CorsMiddleware',
          ...
      ]

Configure allowed origins in `settings.py`:

      CORS_ALLOWED_ORIGINS = [
          "http://localhost:3000",
          # Or any other origins you need
      ]


<p align="right">(<a href="#readme-top">back to top</a>)</p>
