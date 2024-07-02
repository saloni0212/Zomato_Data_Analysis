<h1>Zomato Data Analysis</h1>
    <p>This repository contains a Jupyter notebook that demonstrates data preprocessing and visualization techniques using the Zomato dataset. The notebook covers various steps from loading the dataset to handling missing values, cleaning data, and visualizing key insights.</p>
    
  <h2>Dataset</h2>
    <p>The dataset used in this project is the Zomato dataset, which contains information about various restaurants. Please ensure you have the <code>zomato.csv</code> file in your working directory.</p>
    
  <h2>Prerequisites</h2>
    <p>Make sure you have the following libraries installed:</p>
    <ul>
        <li>pandas</li>
        <li>numpy</li>
        <li>matplotlib</li>
        <li>seaborn</li>
    </ul>
    <p>You can install these libraries using pip:</p>
    <pre><code>pip install pandas numpy matplotlib seaborn</code></pre>
    
   <h2>Project Structure</h2>
    <ul>
        <li><code>Zomato_Data_Analysis.ipynb</code>: The main Jupyter notebook containing the code for data preprocessing and visualization.</li>
    </ul>
  
   <h2>Steps Covered</h2>
    <ol>
        <li><strong>Loading the Dataset</strong>
            <ul>
                <li>Importing necessary libraries</li>
                <li>Loading the dataset using <code>pandas</code></li>
            </ul>
        </li>
        <li><strong>Initial Data Exploration</strong>
            <ul>
                <li>Displaying the first few rows of the dataset</li>
                <li>Checking the shape of the dataset</li>
                <li>Identifying and removing unnecessary columns</li>
            </ul>
        </li>
        <li><strong>Handling Missing Values</strong>
            <ul>
                <li>Summarizing missing values</li>
                <li>Replacing or removing missing values</li>
            </ul>
        </li>
        <li><strong>Data Cleaning</strong>
            <ul>
                <li>Removing punctuation from numeric columns</li>
                <li>Converting data types for numerical operations</li>
                <li>Handling unique and inconsistent values</li>
            </ul>
        </li>
        <li><strong>Data Visualization</strong>
            <ul>
                <li>Bar plots for top-rated restaurants</li>
                <li>Distribution plots for ratings</li>
                <li>Bar plots for restaurant chains</li>
                <li>Analyzing restaurant locations and cuisines</li>
            </ul>
        </li>
    </ol>
    
<h2>Visualizations</h2>
    <p>The notebook includes various visualizations to help understand the distribution and characteristics of the data:</p>
    <ul>
        <li>Bar Plot of Top 15 Restaurants by Rating</li>
        <li>Distribution Plot of Ratings</li>
        <li>Bar Plot of Top Restaurant Chains</li>
        <li>Bar Plot of Highly Rated Restaurants with Most Votes</li>
        <li>Bar Plot of Worst Rated Restaurants</li>
        <li>Count Plot of Restaurant Locations</li>
        <li>Bar Plot of Top 10 Cuisines</li>
    </ul>
    
<h2>Usage</h2>
    <ol>
        <li>Clone this repository:
            <pre><code>git clone https://github.com/saloni0212/zomato-data-analysis.git</code></pre>
        </li>
        <li>Navigate to the project directory:
            <pre><code>cd zomato-data-analysis</code></pre>
        </li>
        <li>Open the Jupyter notebook:
            <pre><code>jupyter notebook Zomato_Data_Analysis.ipynb</code></pre>
        </li>
        <li>Run the cells in the notebook to see the preprocessing and visualization steps in action.</li>
    </ol>
    
<h2>Contributing</h2>
    <p>Contributions are welcome! Please fork the repository and create a pull request with your changes.</p>
    
