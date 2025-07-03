from rest_framework.views import APIView
from rest_framework.response import Response
from rest_framework import status

class HelloAPIView(APIView):
    """
    A simple API view to say hello.
    """
    def get(self, request):
        return Response({"message": "Hello from ALX Travel App API!"}, status=status.HTTP_200_OK)
