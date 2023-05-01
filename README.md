# Kerim's Test App on "B2B Payment Integration POC"

## Setup (development)

To run the application, you will need to have Node.js.

1. Clone the repository: `git clone https://github.com/berdimyradov/test-demo`
2. Install dependencies: `cd test-demo && npm install`
3. Create a `env.local` file using the `env.local.example` as an example
4. Poplulate env variables
   - `MONGODB_URI` - e.g. `mongodb+srv://<username>:<password>@<host>/<database>?retryWrites=true&w=majority`
   - `API_URL` - For local testing set to `http://localhost:3000/api`
5. Start the dev server: `npm run dev`
6. Open `http://localhost:3000` in your browser to access the application.

## Example of this app online

To see an example of running app go [here](https://test-demo-topaz.vercel.app)

## Usage

### Enter Payment Information

To enter payment information, navigate to the "Payment" page and fill out the form with the payee's name, email address, and payment amount. Click the "Submit" button to send the payment information to the server.

### View Payment History

To view payment history, navigate to the "History" page. The page will display a list of all the payments stored in the database.
