GIVEN I want to be able to write and save notes
I WANT to be able to delete notes I've written before
SO THAT I can organize my thoughts and keep track of tasts I need to complete

--Application should allow users to create and save notes.

WHEN User clicks get started
THEN Retrieve the '/notes' path

WHEN User enters data in textarea and clicks save
THEN push 'note' to 'saved notes'

--Application should allow users to view previously saved notes.

WHEN redirected to '/notes' path
THEN render() saved notes if any
ELSE empty()

--Application should allow users to delete previously saved notes.

WHEN user clicks 'DELETE'
THEN the appropriate tast will be empty()