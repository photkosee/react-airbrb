## More functionalities on milstones

### 2.1.1. Login Screen
- Toggle show/hide password
- Disable the submit button until all inputs are assigned for better UX

### 2.1.2. Register Screen
- Toggle show/hide password/confirm password
- Disable the submit button until all inputs are assigned for better UX

### 2.1.4. Items on all screens
- Conditionally display only a button that lead to another screen (not to itself, swtiching from hosting/travelling), and a back button when viewing another screen

### 2.2.1. Hosted Listings Screen
- Also sort listings in an alphabetical order for consistency and better ux

### 2.2.2. Hosted Listing Create
- Allow users to add as many beds as they want

### 2.2.4 Publishing a listing
- Can add more availabilities when publishing

### 2.3.1 Listings Screen
- Having a small chip at the bottom right of each list indicating whether the user is the owner or has booked the list
- Displaying an average star rating helping a user to find the best list, with other important informations

### 2.3.2 Search Filters
- Having a button allowing a user to clear all of the filters applied
- Allowing users to apply multiple filters, and can input only min or max as a filter
- Apply filters automatically when typing or adding new filters (one of the forum post confirmed that this can be counted as one of the bonus features), which will show all the values of filters applied until a user click the clear filters

### 2.4.1 Making a booking and checking its status
- The total price can change according to users booking a new booking
- Allow users to delete a booking they booked with a pending status in a list booking card

### 2.5.2. Viewing booking requests and history for a hosted listing
- For all the booking that'd been accepted or declined, display a chip with the status on the bottom of the booking card for better UX
- Also showing the profit graph of that individual listing similar to 2.6.2

### 2.6.1 Advanced Listing Rating Viewing
- Good looking review cards with a user name, star rating, and feedback
- Allowing users to view this on the landing page as well (but not in each of the individual comment in the review listing card (in the view listing page), since that would be too messy and not a good ux)
- Using stopPropagation to prevent weird interactions when having a tooltip

## Extra functionalities
- Good looking UI and icons for a11y
- toast messages indicating both success and error with meaningful messages
- Validating collaping date inputs, and other inputs. Having constraints (when login-register, and some other forms such as booking, publishing, and more) to give a better ux, preventing users to face an error
- Wrapping all comments to make sure users can leave as long feedback as they like and it'll all be displayed (and for most of the texting part as appropriate)
- Having a confirmation modal for actions such as delete (booking and listing), publish
- Allow users to delete a booking they booked with a pending status in a list booking card
- Allow hosts to delete their own lists
- Displaying a review section in each list with a user name, feedback, and star rating (and could be clicked to view all other reviews just like 2.6.1), making the card scrollable (for both displaying reviews and booking history to support many elements)

### Side note for 2.6.3. Listing Upload
The testing JSON file is in the `frontend` directory with the name `create.json`

## We are using Tailwind CSS, so pleaes don't delete `globals.css` file when testing the demo since the file is only for configuring the framework
