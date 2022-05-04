## Blockchain Ledger

The purpose of this project is to create a blockchain ledger system that is deployed with a user-friendly web interface. The blockchain ledger is written in Python and is deployed using Streamlit. The ledger's goal is to conduct financial transactions and verify the integrity of the data contained in the ledger. 

---

## Using the Ledger

Use the terminal to run the following: streamlit run pychain.py. This will open your browser and display the ledger. Simply type in a value for the sender, receiver, and amount. Once this is completed, click "Add Block" to add the transaction to the ledger. You will see a new entry appear in the ledger with the record, creator ID, previous hash, timestamp, and nonce listed. The 'validate chain' button below the ledger can be clicked to ensure the integrity of the data. On the left side of the screen, you can adjust the block difficulty and explore the block inspector that will allow you to get the specific information contained in previous blocks. A screenshot of the deployed application is below:

![pychain](https://raw.githubusercontent.com/tycastleberry/Challenge18/main/pychain.png)

---

## Contributors

Tyler Castleberry was the sole contributor to this project. 

---

## License

MIT License

Copyright (c) 2022 Tyler Castleberry

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.