# Test #1 - Address Formatting Test

In this test you are tasked with breaking out a long address string into it's individual address parts (eg. street address, city, postal, etc).

## Instructions

Click here to download the [address_formatting_test.xlsx](address_formatting_test.xlsx?raw=true) spreadsheet and open it in Excel. You'll see something that looks like the image below.

![](test.png)

You'll see that the data in Column B contains a full mailing address.

**Your job is to break out the individual address parts (eg. street, city, postal, etc.) into the corresponding columns (C to H).**

There are two examples, so just follow along with this. The resulting file should look similar to the below when complete.

![](results.png)

Save the updated file and email it back to us

### Hints and notes to help you out

- Sort the data and look for patterns
- The `mail_address2` column is optional, some of the USA entries may not have a `mail_address2` and that's OK!
- (Advanced) If you're feeling a bit adventurous, Google "Excel split text delimiter"

## What are we testing for?

When we onboard a customer, we must first load in the data for their voters into our system. The "customer data" is typically sent to us in a spreadsheet format (`xlsx`, or `csv`). However, the customer data is usually not in a format that our system can understand. We need to reformat the data into something we can use.

We call the process of reformatting customer data **"data cleaning"**.

## The next test

Be sure to complete [Test #2](../2_fee_lookup) before sending us an email.


_Disclaimer: All data used in this test was mocked using a random data generator. Any relation to real world data would be by pure coincidence_
