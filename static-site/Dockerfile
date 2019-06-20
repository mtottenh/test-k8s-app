# Use the 'onbuild' layer as a base to get Docker to setup our requriements.txt
FROM python:3-onbuild

# Flask will use port 5000 by default
EXPOSE 5000

CMD ["python", "./app/main.py"]
