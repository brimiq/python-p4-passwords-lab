# TODO: Make all tests pass

## Issues Identified:
1. User model missing `to_dict()` method
2. Login resource not implemented
3. CheckSession resource not implemented
4. Logout resource not implemented

## Plan:
1. Add `to_dict()` method to User model in models.py
2. Implement Login.post() in app.py
3. Implement CheckSession.get() in app.py
4. Implement Logout.delete() in app.py
5. Register new resources with api
6. Run tests to verify

