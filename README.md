
# Moodle Copy Course From CLI

A little script used to copy a course from the terminal just like you'd do from the GUI.

> [!WARNING]
> This script was originally made to be used in my environment. Changes needs to be done to follow your needs.

## Installation

just copy the two scripts inside the moodle root directory (moodle code root, NOT moodledata).

> [!CAUTION]
> Use the same user that launches moodle to execute the script or it won't have the expected behavior!

## Usage

`script_get_course.php` shows you all scripts that aren't part of Archive category and allows you to save the IDs to `course_ids.txt`.  
`script_update_course.php` Allows you to copy all courses contained in the previous .txt file OR to update one with a given ID.
