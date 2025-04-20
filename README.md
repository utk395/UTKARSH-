User Name Editing After Registration

Implemented functionality allowing users to update their registered names directly from the dApp interface.

✅ Solidity changes included:

Added an updatePersonName() function with proper validations.

Emitted a PersonNameUpdated event to notify front-end or external listeners.

✅ Frontend (JSX) changes:

Created an editable input field toggled by an “Edit Name” button.

Integrated blockchain interaction to update the name and reflect it locally upon confirmation


Wallet Address Display

Users can now view their connected wallet address directly on the screen:

jsx
<p>Account: {account}</p>
