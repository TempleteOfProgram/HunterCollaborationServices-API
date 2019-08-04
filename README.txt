#Retrieving parameters from a URL
    import urlparse
    url = 'http://www.example.com/?def=ghi'
    parsed = urlparse.urlparse(url)
    print urlparse.parse_qs(parsed.query)['def']


1. Serives.data.DBConn.py has database url.
2. api.UserAPI.py has REGISTER-new-user method
3. api.AuthorizationAPI.py has LOGIN method
4. api.CollaborationAPI.py has Collaboration method
5. api.MessagingAPI.py has MessagingAPI method
