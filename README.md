# openai-quickstart-vue

This is a quickstart template for using OpenAI's GPT-3.5 API in Vue 3.

![image](./assets/preview.png)

## Setup

1. Clone this repository and navigate into the project directory

    ```shell
    git clone https://github.com/nephen/openai-quickstart-vue.git
    cd openai-quickstart-vue
    ```

2. Using `pnpm` to install dependencies
  
    ```shell
    pnpm install
    ```

3. Create the `.env` file to store your OpenAI API key and Orgnaization ID

    ```shell
    touch .env
    ```

4. Add your OpenAI API key and Orgnaization ID to the `.env` file

    ```shell
    # Example
    VITE_CHAT_URL=xxxxxxx
    VITE_CHAT_TOKEN=xxxxxxxx
    ```

5. Run the development server, and open [http://localhost:5173](http://localhost:5173) in your browser

    ```shell
    pnpm dev
    ```

6. Build the project for production

    ```shell
    pnpm build
    ```
