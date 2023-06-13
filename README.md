# wso2is
WSO2 Identity Server 

# To run first of all build the docker image
# from the wso2is folder run 
docker build -t wso2is .

# Once the image is ready
docker run -d -p 9443:9443 -v /Users/oleksiybozhyk/Documents/FORMAZIONE_SVILUPPO/wso2is/wso2is/files/:/home/wso2carbon/wso2-config-volume wso2is