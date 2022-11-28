This repo host the docker for the DOMtutor/DOMjudge system.
This docker was created by [Tobias Meggendorfer](https://github.com/incaseoftrouble)

# Deployment

 * Create `domjudge/.env` with:
   ```
   DB_ROOT_PASSWORD=<secure password>
   DB_DOMJUDGE_PASSWORD=<secure password>
   ```
 * Run `docker-compose up -d`
 * Note the judgehost secret
 * Add to `.env`:
   ```
   JUDGE_PASSWORD=<judgehost secret>
   ```
 * Run `docker-compose up -d`


