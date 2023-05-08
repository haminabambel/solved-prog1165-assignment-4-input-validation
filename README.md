Download Link: https://assignmentchef.com/product/solved-prog1165-assignment-4-input-validation
<br>
Your requirements list for input validation should not be a formal document.

It must be a text document called req.txt. It must have the first and last names of each group member at the top.

The requirements should be a bulleted list oriented towards being friendly for the user while still maintaining the integrity of the input data.

Your unique identifier will be provided as part of the feedback to your submission in D2L.

<strong>Milestone 2 – The Program</strong>

Create a program that takes input for an address book (of people, not businesses), validates the input, and stores the data in an array. Once the user has entered the desired number of entries, the address book should be displayed in its entirety.

The data stored consists of:

<ul>

 <li>Name (maximum length 30 characters)</li>

 <li>Street Address (maximum length 60 characters)</li>

 <li>City (maximum length 60 characters)</li>

 <li>Province (in the format of a 2 character long Canadian province abbreviation used by Canada Post)</li>

 <li>Postal Code (in the format of a Canadian Postal Code)</li>

 <li>Phone Number, including area code</li>

</ul>

As noted earlier, the specific requirements for input validation will be provided after the first deadline. It is a compilation of all submitted requirements.

You must prompt the user in a user-friendly way. This requires that the prompt be informative but not overbearing.

If the user enters invalid input, an error message must be displayed indicating what the problem is. The user must be given an option as to whether to skip entering this part of the address book entry (e.g. skip the Address and continue with the City) or to try again.

The array of addresses is of size 10. The user will be permitted to enter up to 10 entries. If the user chooses to end entry early, they can specify this by pressing ENTER as the first and only character of the name (this is the lone exception to the “pressing ENTER skips a component” requirement).

Once the user has done 10 entries or has chosen to end entry early, the program will then display the contents of the address book, three entries on a page. Each entry will be five lines in size. The lines must be in the following format:

Fred Flintstone

11 Cobblestone Lane

Bedrock, ON, N2Y 3E8

519-555-1212




Paginate your output properly (the user should not have to scroll to see output of a single address book entry.

Do not use regular expressions or any third-party libraries for this assignment.

When the program starts up, display the name (string) that your group has been assigned after Milestone 1. This will uniquely identify your assignment. Do not put any other identifying information (e.g. “Fred’s Address Book) in the program.

Call your executable file astA4.exe.

Submit your solutions (cleaned) <strong>and your executable</strong> to the appropriate dropbox. If you do not have an executable submitted for this assignment, you will lose 40% of the marks assigned to milestone 2.




NM








