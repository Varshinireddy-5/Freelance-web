# SkillConnecto

SkillConnecto is a freelancing platform that connects skilled professionals with clients seeking services across various domains. It enables freelancers to showcase their expertise, bid on projects, and collaborate with clients efficiently.

## Features
- User authentication and profile management
- Project posting and bidding system
- Secure payments and transaction tracking
- Real-time messaging between clients and freelancers
- Admin panel for managing users and projects

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/skillconnecto.git
   cd skillconnecto
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Set up environment variables by renaming `.env.example` to `.env` and configuring necessary values.

5. Run the application:
   ```bash
   uvicorn app.main:app --reload
   ```

6. Access the API at `http://127.0.0.1:8000`

## Usage
- Sign up or log in as a freelancer or client
- Clients can post projects and freelancers can bid
- Secure payments ensure trust between users
- Admins can oversee and manage platform activities

## Contributing
Contributions are welcome! Feel free to submit a pull request or report issues.


