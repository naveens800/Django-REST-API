# Django-REST-API
Created a simple REST API with django rest_framework which will interact between user and
system or server for fetching details stored in MariaDB ( is a fork of Mysql ).
The Database consist of  2 fields (1.Name of Country, 2.Capital of that country ).





There are two views in views.py file, 1.countries_list (which can accept GET and POST ), 2.Countries_details (which can accept GET, PUT and DELETE)

1.GET- To retrive resources
2.POST-To create resources
2.PUT-To update resources
4.DELETE- To delete resources

The 1st view will give all the list of countries and their captals respectively
The 2nd view will give specific details of country.

User can perform all the operations as mentioned above.

Requirements :
1.MariaDB
2.django rest_framework
3 python3

