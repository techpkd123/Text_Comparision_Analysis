# Text_Comparision_Analysis

### I have created two text files(blog1.txt and blog2.txt) where I have pasted the textual content from two blogs related to placement experience of two students in different fields.One in MBA and another in Software Engineering and compare the similarities in their experience using NLP and text analytics.

# Final Result we get:-

Code

    percentage_of_similarity = round(float((sum_of_sims / len(file_docs)) * 100))
    print(f'Average similarity float: {float(sum_of_sims / len(file_docs))}')
    print(f'Average similarity percentage: {float(sum_of_sims / len(file_docs)) * 100}')
    print(f'Average similarity rounded percentage: {percentage_of_similarity}')
##### Ouput
      Average similarity float: 0.10320120056470235
     Average similarity percentage: 10.320120056470234
     Average similarity rounded percentage: 10
# Installation Instructions

 First ensure you have all dependencies installed using:-
 
         pip install nltk
         pip install gensim
         
After that clone the repo using:-
    
          git clone https://github.com/techpkd123/Text_Comparision_Analysis.git
          
# Now you are good to go and start exploring the notebook which i made          

