# intproapi

Install the required dependencies using pip:
pip install -r requirements.txt

Rename the intpro directory to your project name.
Update the database settings in intpro/settings.py if necessary.
Apply the database migrations:
python manage.py migrate

python manage.py runserver

python manage.py createsuperuser


API Endpoints
The following API endpoints are available:

Add Audio Element: POST /audio-element/add/
Get Audio Element by ID: GET /audio-element/<audio_element_id>/
Delete Audio Element by ID: DELETE /audio-element/<audio_element_id>/delete/
Update Audio Element by ID: PUT /audio-element/<audio_element_id>/update/
Get Audio Fragments: GET /audio-fragments/?start_time=<start_time>&end_time=<end_time>
