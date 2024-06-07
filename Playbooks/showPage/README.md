# Run command.
ansible-playbook -i inventory.yml showPage.yml --limit 'machine'
                             
                                 
                                 ### Tags available  ####

# To install Docker + Docker-compose also to ensure that Docker is running on server.
- initDocker

# To generate docker-compose file from template !! image extra var is required for this.
# To create application directory.
cp_compose



# To build that image this tag is used
buildImage




                                    ###  Extra vars available ###
    
# To indicate image
image

# To expose port of application (default: 8080)
exposed_port

# To set base_url (default: 'http://192.168.99.16:8080')
base_url