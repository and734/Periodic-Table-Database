Intructions

----------------------------------------------------------------------------
1.Compact sql db queries into periodic_table.sql
----------------------------------------------------------------------------
pg_dump -cC --inserts -U freecodecamp periodic_table > periodic_table.sql

----------------------------------------------------------------------------
2.Prepare git directory
----------------------------------------------------------------------------
mkdir periodic_table
cd periodic_table
git init
git checkout -b main
git commit -m "Initial commit"

----------------------------------------------------------------------------
3.Prepare shell scipt files
----------------------------------------------------------------------------
touch element.sh
touch fix_database.sh
chmod +x element.sh
chmod +x fix_database.sh
----------------------------------------------------------------------------
4. Copy scipts and run the scripts (fix db first)
----------------------------------------------------------------------------
touch periodic_table.sql
git add periodic_table.sql
git commit -m "fix: Add database schema with constraints"

git add element.sh
git commit -m "feat: Add element lookup script"

git add element.sh
git commit -m "refactor: Improve SQL query and error handling"

git add .
git commit -m "chore: Final cleanup before submission"


_______________________________
to check the log
_______________________________
git log --oneline




