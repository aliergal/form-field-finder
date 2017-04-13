# form-field-finder

Install Perl

curl -L http://xrl.us/installperlosx | bash


Download source code of the website

wget http://example.com > page.html

if wget doesn't work then use

curl http://example.com > page.html


Export Report

perl formfinder < page.html


Curl command to submit form

curl --data "first_name=FirstName&surname=Surname" "form_action_url"
