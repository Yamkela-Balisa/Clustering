In the Cluster.py i created a class called Cluster and two static functions 
  - first function is  output_into_file() , takes one arguments the list contain ouput data
  - function open file and write ouput to it
  - second function main () to make object of class cluster and invoke the class

class Cluster contains :
    
    __init__() to construct class cluster 
      - field are intitialised inside this function
      - takes no argument, there for defaulted constructor
    set and get function for data manipulation and encapslation for each data field
    
    generate_new_centre(cluster, cluster_number) take cluster and cluster number
     - generate new centriod for given data (cluster) and cluster number 
     - comments on code give more details and git logs
     
    generate_new_clusters() take no argument
     - generate data point for new generated cluster centriod 
     - More infor given on comments how new cluster are generated
    
     convergence() take no argument
      - check if centriod are converging 
      - at converging state of centriod data is stored about each cluster and number of iterartion
      - Refer to comments how the function check convergence
     
      output_format () take no argument 
       - format the output of the class cluster
       - refer comments code for more information
       
    
    
  

