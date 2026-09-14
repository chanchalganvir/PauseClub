# PauseClub - ChatGPT Connector

A simple ChatGPT connector for PauseClub.

## Setup

1. **Install dependencies**:
   ```bash
   npm install
   ```

2. **Get your OpenAI API key**:
   - Go to [OpenAI Platform](https://platform.openai.com/api-keys)
   - Create a new API key
   - Copy the key

3. **Configure environment**:
   - Copy `.env.example` to `.env`
   - Add your OpenAI API key:
     ```
     OPENAI_API_KEY=your_key_here
     ```

4. **Run the connector**:
   ```bash
   npm start
   ```

## Usage

```javascript
const { chatWithGPT } = require('./index.js');

const response = await chatWithGPT('Your message here');
console.log(response);
```

## Development

Run with auto-reload:
```bash
npm run dev
```

## Notes

- Make sure your OpenAI account has credits available
- Keep your API key private and never commit `.env` files
- Check OpenAI pricing before extensive use
