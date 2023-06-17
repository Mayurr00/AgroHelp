# AgroHelp
AgroHelp is a machine learning and deep learning based project aimed at assisting farmers in their agricultural practices. The project revolves around a user-friendly website designed specifically for farmers. The website provides a comprehensive solution to farmers by enabling them to check for diseases in their crops. It achieves this by utilizing ML algorithms trained on crop disease datasets to accurately identify and diagnose crop diseases based on uploaded images.
Additionally, AgroHelp integrates soil analysis capabilities by leveraging live API data. This feature allows farmers to analyze the soil composition of their fields, providing valuable insights into nutrient levels and soil health. Based on the soil analysis results, AgroHelp recommends suitable secondary crops that can be grown profitably in the specific area. This empowers farmers to diversify their agricultural activities and maximize their income. The project aims to streamline and optimize farming practices, leading to increased crop yield, minimized crop diseases, and improved overall farm productivity. AgroHelp serves as a one-stop platform for farmers, combining disease detection, soil analysis, and crop recommendations, all accessible through a user-friendly website interface. By harnessing the power of ML and DL technologies, AgroHelp seeks to revolutionize the way farmers approach crop management, ultimately enhancing their livelihoods and contributing to sustainable agriculture practices.


# How to use
To download the Money Maven project from both the main and master branches, follow these steps:
1. Navigate to the repository on GitHub.
2. Click on the "Code" button and select "Download ZIP".
3. Extract the ZIP file to your desired location.
4. Open the extracted folder and navigate to the "main" and "master" branches.
5. You can download each branch individually by clicking on the "Code" button and selecting "Download ZIP" for each branch.</br></br>

Alternatively, you can clone the repository using Git and switch between the main and master branches using the following commands: </br>
$ git clone <repository URL> 
</br>
$ cd <repository name> 
</br>
$ git checkout main </br>
</br>
To switch to the master branch, use the following command: </br>
$ git checkout master

# How to run this project
To run the project, follow these steps in your terminal:

1. Navigate to the client directory: 
$ cd client
2. Start the React development server:
$ npm run dev
3. Keep the React server running and open a new terminal window or tab.
Navigate back to the project root directory.
Run the Flask server:
$ python app.py
</br>
Now, you should have both the React frontend and Flask backend running simultaneously. The React development server will handle the frontend of the website, while the Flask server will handle the backend logic and API communication. You can access the website by opening a web browser and visiting the provided localhost URL.

# Technology used
1. React: A JavaScript library used for building the user interface of the website, providing a responsive and interactive user experience.
2. Flask: A micro web framework in Python used for building the backend of the website, handling data processing and communication with the frontend.
3. Machine Learning and Deep Learning Algorithms: These algorithms are used to analyze crop diseases and recommend secondary profitable crops based on soil analysis, leveraging ML and DL techniques for accurate predictions.
4. Firebase: A real-time database and authentication service provided by Google, used for storing and managing user data, crop disease information, and soil analysis results securely.
5. Mapbox API: An API that provides mapping and location-based services, used to display maps and visualize geographical data, enabling farmers to identify their location and explore nearby resources.
6. Ambee API: An environmental intelligence platform API that provides real-time data on air quality, weather conditions, and other environmental factors, used to enhance the accuracy of disease prediction and crop recommendations based on current environmental conditions.



