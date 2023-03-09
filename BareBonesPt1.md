# Notes for Week 8: Create a Bare Bones OPAC, Part 1
## Notes taken as I progress through the lesson. Note taking done via Notepad,
then I plan to copy and paste into command line to upload it to GitHub.

1. Updates were suggested upon login: ran sudo apt update
Then I ran apt list --upgradable

Then finally sup apt upgrade

Had to enter Y to approve install and use additional memory space.

Finally, ran clear
to clear out the screen.

2. First, I read through the transcript on the website. WOW. I feel like I just read something
in a foreign language. I am working with HTML and JS in LIS636 right now and with MqSQL in LIS658,
but I still feel lost.

3. Watching the videos, it was all information I knew from my other classes;
my main issue was not remembering last week's process. So instead of easily copy/paste, I have to
re-watch last week.

4. I logged into MySQL by using mysql -u opacuser -p  and typed my password.

5. After log in, I typed show databases;
and selected a database by typing
use opacdb;
and the database was changed.

5. To show the table I would add information to, I typed
show tables;

6. Insert information into the table: 
insert into books (author, title, publisher, copyright) values

('Eric Carle', 'The Very Hungry Catepillar', 'World Publishing Company', '1969-06-03'),
('Maurice Sendak', 'Where the Wild Things Are', 'HarperCollins', '1963-11-13'),
('Patricia Polacco', 'Thunder Cake', 'Puffin Books', '1990-01-01'),
('Elin Kelysey', 'You are Stardust', 'Owlkids', '2012-09-11'),
('Deborah Marcero', 'In a Jar', 'Penguin Random House', '2020-01-21'),
('Eric Fan', 'Night Lunch', 'Tundra Books', '2022-09-27');

*Realized each row needs to end in a comma, not semicolon, except for the last row.

