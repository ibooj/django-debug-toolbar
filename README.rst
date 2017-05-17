====================
Django Debug Toolbar
====================

DATABASE_ENGINE = 'mysql'

INSTALLED_APPS += ('debug_toolbar',)

INTERNAL_IPS = ('127.0.0.1', '192.168.33.1')

MIDDLEWARE_CLASSES += ('debug_toolbar.middleware.DebugToolbarMiddleware',)
