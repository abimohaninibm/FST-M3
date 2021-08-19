	
# Specify Base Image
	
FROM node:alpine
	

	
# Work Directory
	
WORKDIR /usr/app
	
# Copy the files

COPY ./ ./  
	
# Install Dependencies
	
RUN npm install
	
 
	
# Startup Command
	
CMD ["npm", "start"]