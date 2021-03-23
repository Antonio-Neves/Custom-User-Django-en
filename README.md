# Custom User Django - English

Custom User Model, Authentication, Templates, Email as username

<p>Warning: Define 'Custom User model' in 'settings.py' file.</p>
<pre>AUTH_USER_MODEL = 'accounts.CustomUser'</pre>
<p>And in 'settings.py' to, the app where is the custom user model, must be before 'django.contrib.admin',</p>
<pre>
# Application definition
INSTALLED_APPS = [
    'accounts',
    'django.contrib.admin',
    'django.contrib.auth',
    'django.contrib.contenttypes',
</pre>

<br><a href="https://ansistemas.com/custom_user_django/" target="_blank">Live Preview</a>

<br><img src="https://ansistemas.com/images/CustomUserDjango-FaceTwit.jpg" style="width:640px;height:auto;">

Attention:  
To hide sensitive values in the settings.py file, such as directions and passwords, I use Python Decouple.  
Instructions at https://pypi.org/project/python-decouple/  
In the repository, rename the file '.env.example' to '.env' and make the necessary changes to your data.

