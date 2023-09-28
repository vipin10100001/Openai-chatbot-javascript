
# OPEN-AI CHATBOT USING JAVASCRIPT

A simple chatbot made using JavaScript and OPENAI API.



## Axios Library usage

// Use axios library to make a POST request to the OpenAI API


  const response = await axios.post(
  
   "https://api.openai.com/v1/completions",
    {
      prompt: message,
      model: "text-davinci-003",
      temperature: 0,
      max_tokens: 1000,
      top_p: 1,
      frequency_penalty: 0.0,
      presence_penalty: 0.0,
    },
    {
      headers: {
        "Content-Type": "application/json",
        Authorization: `Bearer ${apiKey}`,
      },
    }); const chatbotResponse = response.data.choices[0].text;

    




## Feedback

If you have any feedback, please reach out to us at vipintestmail03@gmail.com


## SCREENSHOT ATTACHED IN THE FILES DO CHECKOUT

