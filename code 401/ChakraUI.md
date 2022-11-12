# Readings: Chakra UI

1. What is a Chakra UI?

- Chakra UI is a component-based library. It's made up of basic building blocks that can help you build the front-end of your web application.

It is customizable and reusable, and most importantly it supports ReactJs, along with some other libraries too.

2. Is Chakra UI better than material UI?

- Material UI is much better when it comes to performance and reliability. Chakra UI is not bad in terms of performance, but it can lag a bit on data-heavy, large-enterprise websites.


3. How to use Chakra UI?

    1. **run one of the following commands in your terminal:**

            - npm i @chakra-ui/react @emotion/react @emotion/styled framer-motion

            - yarn add @chakra-ui/react @emotion/react @emotion/styled framer-motion

            - pnpm add @chakra-ui/react @emotion/react @emotion/styled framer-motion

    2. After installing Chakra UI, you need to set up the ChakraProvider at the root of your application. This can be either in your index.jsx, index.tsx or App.jsx depending on the framework you use.

            import * as React from 'react'

            // 1. import `ChakraProvider` component
            import { ChakraProvider } from '@chakra-ui/react'

            function App() {
            // 2. Wrap ChakraProvider at the root of your app
            return (
             <ChakraProvider>
                 <TheRestOfYourApplication />
             </ChakraProvider>
                 )}