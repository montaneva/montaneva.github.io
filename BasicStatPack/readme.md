This repository serves as a comprehensive collection of client-oriented web tools, crafted by OpenAI's ChatGPT, for statistical analysis. 

Below is a brief overview of the tools available in this repository. Each tool has been developed with a specific purpose and offers unique functionality to assist you in your statistical analysis tasks:

1. **multi-statistics-calculator.html**  
   A comprehensive tool for numerical datasets, facilitating the computation of diverse statistical metrics including mean, median, mode, standard deviation, quartiles and more.

2. **odds-ratios-calculator.html**  
   A calculator specifically designed to compute odds ratios for your data with 95% confidence intervals and Chi-Square method P-value..

3. **percentage-proportions-calculator.html**  
   A simple and efficient tool to calculate proportions in percentages, helping you to easily interpret your data in percentage terms.

4. **wilson-score-interval.html**  
   This tool calculates 95% confidence intervals using the Wilson score interval method, providing a more accurate estimate.


# Prompt
For a deeper understanding of the method that led to the creation of these tools using OpenAI's ChatGPT or any other advanced artificial intelligence language model, please find below the original prompt:

````
I need your assistance in developing a client-oriented web tool with the following features:

Required Tool: [Specify the purpose or function of the tool]

Technical Specifications:

- Frontend: Develop using HTML for structure, CSS for styling, and JavaScript for functionality.
- Libraries: Incorporate Bootstrap (via CDN) for responsive design and styling, and jQuery (if necessary) for DOM manipulation.
- Styling: Ensure a user-friendly experience with a modern, responsive and clean design.
- Form Validation: Validate user inputs to ensure all sample values are between 0 and the total population, with the population greater than 0.
- Dynamic Output: Display results dynamically on the same page without reloading, hiding rows with sample values of 0 in the output table.
- Reset Functionality: Provide a reset button to clear both the form and results.

Upon completion, include instructions for implementing and testing the code using a text editor and a web browser, particularly aimed at users with limited coding experience.


A valid html template could be:

<!DOCTYPE html>
<html lang="en">
 <head>
    <meta charset="UTF-8">
    <meta name="robot" content="noindex">
    <meta name="description" content="">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title></title>
	
    <!-- Bootstrap CSS -->
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
	
	<!-- Additionnal styling rules --> 
    <style>
    </style>
	
 </head>
 <body>
    <div class="row justify-content-center">
        <div class="col-12 col-sm-10 col-md-8 col-lg-6 col-xl-4">
            <h4 class="text-center mt-3 mb-3"><!-- Title --></h4>

            <form id="calcForm" class="mb-4">
		 <!-- The main form goes here-->
            </form>

            <div id="results"></div>
            
            <div id="guidelines">
                <div>
                    <div id="headingOne" class="text-center mt-3 mb-1">
                        <button class="btn btn-link" data-toggle="collapse" data-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
                           Guidelines
                        </button>
                    </div>

                    <div id="collapseOne" class="collapse" aria-labelledby="headingOne" data-parent="#guidelines">
                        <div class="card-body">
                            <ul id="guidelinesList" style="font-size:85%; padding:0">
								<li><!-- Lorem ipsum... --></li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>

            <hr />
			
            <div id="footer">
                <p class="text-center">
				<!-- Lorem ipsum... -->
                </p>        
            </div>
        </div>
    </div>

    <!-- Bootstrap JS and dependencies -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.4/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
 
	<!-- Additionnal Javascript --> 
    <script>
    </script>

 </body>
</html>

````

