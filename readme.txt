1. I have uploaded the screenshots of my work done in /images folder.

2. Customers
          |
           - Create account
           - Login
           - View/Track Submitted Request
           - Add Request: Create a new service request.
           - (Provide Options to view request type)
           - Optional : Upload files
           - View Account Info: View/update their account details.

   System (Team):
          |
           - Provide Support

   Admin
          |
	   - View all Requests
           - Update Status (Pending, In-progrees, Completed)
	
   Notifications: Future Work(Extras - Send Email)
          |
	   - Notify customers when their request status changes
           - Similarly, notify admin when a new request is submitted.
           - On request completion, as for FEEDBACK and send email to customer.

3. Structure : 
   
   Gas_utility
        |
          - customer_service
                   |
                    -  _pycache_
                    -  migrations
                    -  templates
                           |
                            - all_service_requests.html
                            - service_request.html
                            - staff_service_requests.html
                            - success.html
                            - track_requests.html
                    - __init__.py
                    - admin.py
                    - apps.py
                    - forms.py
                    - models.py
                    - tests.py
                    - urls.py
                    - views.py
          - gas_utility
                   |
                    - __pycache__
                    - __init__.py
                    - asgi.py
                    - settings.py
                    - urls.py
                    - wsgi.py
                    - /media
                         |
                          - (uploaded_fileS)
                    - db.sqlite3
                    - manage.py