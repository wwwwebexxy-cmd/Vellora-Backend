# Vellora Backend

This backend is intentionally local/configuration-only. No previous project's
database, deployment settings, fixtures, uploads, or seed catalog are included.

1. Copy `.env.example` to `.env`.
2. Create a new database and fill the `VELLORA_*` values with new credentials.
3. Run `python manage.py migrate` and `python manage.py createsuperuser`.
4. Start the API with `python manage.py runserver`.

Create the catalog, media, banners, and other records manually through the
admin/dashboard workflow.
