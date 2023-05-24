# flask_app_apache

This role takes a git repo and Flask application name as input, and deploys
the application to a server.

It makes the following assumptions:

 * You are using Flask
 * You are using virtualenv
 * You want to use Apache proxied to a Gunicorn instance
 * You want the application deployed to a subdirectory on the server
 * You are using CentOS or RHEL

## Role Variables

    project_name=<my project name>
    repo_url=<project repository>
    webserver_name=<fully qualified domain name>
    vhost_shortname=<vhost short name>
    

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - flask_app

## License

MIT

## Author Information

DLI
