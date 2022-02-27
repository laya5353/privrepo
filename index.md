## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/laya5353/privrepo/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.



<head> 
      <title>Determine the Optimal Location for your Startup</title>  <!--title name-->
      <meta name="viewport" content="width=device-width, initial-scale=1"> <!--width and scale-->
      <meta name="apple-mobile-web-app-capable" content="yes"> <!--accessible on apple mobile-->
      <link rel="stylesheet" href="w3.css"> <!--style formatting-->
      <link rel="stylesheet" href="w3-colors-flat.css"> <!--color formatting-->
   </head> 


<script> //start javascript
	var anxiety_count = 0; //initialized number of anxiety symptoms to 0
   	var stress_count = 0; //initialized number of stress symptoms to 0

        function anxietyAdd(){ //function for anxiety symptom counting
            anxiety_count = anxiety_count + 1; //adds one to anxiety count everytime a button correlating to anxiety symptoms is clicked

        }

        function stressAdd(){ //function for stress symptom counting
            stress_count = stress_count + 1; //adds one to stress count every time a button correlating to stress symptoms is clicked
        }
	
	function percentageResult(){ //function to create results in percentage form
		var anxietyPercent = anxiety_count / 4 * 100; //calculates percentage of anxiety symptoms based on anxiety count variable
		var stressPercent = stress_count / 4 * 100; //calculate percentage of stress symptoms based on stress count variable
		var resultText = document.getElementById("resultsopen"); //added variable to show results
		resultText.innerHTML = "Probability it is an anxiety disorder = " + anxietyPercent + "% <br> Probability it is stress = " + stressPercent + "%"; 
		//added inner HTML command to show probabilities of stress and anxiety
	
// The following code lets you know when the file was last modified.
// This will help you know if you are looking at the new version of the file or if there is a delay on GitHub.
       var docMod = document.lastModified;
       console.log("This file last modified  " + docMod);
// commented out alert box that shows last modification time and date


	
	}
	

  </script>




### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/laya5353/privrepo/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
