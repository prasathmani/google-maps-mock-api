# Google Maps Mock API
This is a mock for use when JS unit testing google maps

I created this mock based on frustration of not finding a more completely mocked google service out there. If you are getting the error "Uncaught ReferenceError: google is not defined" or similar when running your Karma tests because you are utilizing google maps to tap into Googles Map and Places Services, this should help.

! If you run into other errors where methods are undefined, add them as methods in the correct spot in the mock google object's tree.
