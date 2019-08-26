# SPECTRA
Giving the path to a java project, Spectra tool compiles a taxonomy of all class level complexity metrics based on method and statement level metrics. 

Also, given a path to a java file, the tool can also output the set of method level or statement level complexity metrics, described bellow, if specified in the command.

The tool can compute the set of complexity metrics for any java project and outputs the result to a specified .csv file. Each line consisting of the path to the file, name of the class or method, and followed by the set of comma separated metric values.
# Prerequisites
For the tool to be compiled and run succefully, the user needs to make sure the following are installed:
- JDK 8 or higher
- Maven 3 or higher

# Compile and run

        git clone https://github.com/issararab/SPECTRA.git
        cd SPECTRA
        mvn clean install
        
The Jar file of the tool will be available in 'target' folder named 'spectra.jar'. You can move it to any desired folder and run as follows:
        
        java -jar spectra.jar <path_to_java_project> <path_to_output_csv_file>
        
 # Metrics
 The method and class level metrics are based on statement level metrics described bellow.
 
 ## Statement level metrics
 
 ## Method level metrics
 
 ## Class level metrics
