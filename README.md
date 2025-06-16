<!DOCTYPE html>
<html lang="sq">
<head>
  <meta charset="UTF-8">
  <title>Sistemet me Agjentë të Shumëfishtë dhe Kujtesë në LLM</title>
</head>
<body>
  <h1>Sistemet me Agjentë të Shumëfishtë dhe Kujtesë në Modelet Gjuhësore të Mëdha (LLM)</h1>
  <h2>Ndërtimi i një Inteligjence Artificiale që Bashkëpunon dhe Mëson në Mënyrë Autonome</h2>

  <h3>Pse lindi ky projekt?</h3>
  <p>
    <strong>asistent inteligjent</strong> që ndihmon në 
    <strong>analizën dhe interpretimin e surveys</strong> per platformen 
    <a href="https://www.questionpro.com" target="_blank">questionpro.com</a> e cila ka miliona perdorues.
    Kërkohej një sistem që:
  </p>
  <ul>
    <li>Kupton kontekstin e pyetjeve dhe përgjigjeve në mënyrë <strong>dinamike</strong></li>
    <li>Mban mend <strong>bashkëbisedimet</strong> e kaluara</li>
    <li><strong>Mëson dhe përshtatet</strong> në mënyrë autonome</li>
  </ul>

  <h4>Teknologjitë kryesore të përdorura:</h4>
  <ul>
    <li><a href="https://www.langchain.com" target="_blank">Langchain</a> – agjent per krijimin e embeddings dhe per marrjen e te dhenave</li>
    <li><a href="https://platform.openai.com" target="_blank">OpenAI GPT</a> </li>
    <li><a href="https://www.pinecone.io" target="_blank">Pinecone</a> – për <strong>kujtesën semantike</strong> (vektorë)</li>
  </ul>

  <hr>

  <h3>Si funksionon një LLM?</h3>
  <p>Semantika ne embeddings</p>
  <img src="https://www.kdnuggets.com/wp-content/uploads/arya_vector_databases_important_llms_3.png" />

  <p> Llojet e embeddings</p>
 
  <p> all-MiniLM-L6-v2 – i shpejte, i mire per kerkim semantik </p>
 <p>BAAI/bge-base-en-v1.5 – shume i mire per rikthim informacioni</p>
 <p>paraphrase-MiniLM-L6-v2 – i lehte, performance e pranueshme</p>
 <p>intfloat/e5-base – i trajnuar per kerkesa me te ndryshme</p>
 <p>microsoft/mpnet-base – me i sakte, por me i ngadalte </p>

 <b> Ruajtja e embeddings </b>
 <img src="https://i.imgur.com/SgCr687.jpeg" />

 <b> Si duket nje 3D databaze me vektor </b>  
 <img src="https://matthewmanela.com/wp-content/uploads/2023/10/image-3.png" />
  <hr>

  

  <h3>Qëllimi</h3>
  <p>
    Të krijohet një sistem ku <strong>agjentet bashkëpunojne</strong>, ruajnë informacionin dhe 
    <strong>marrin vendime</strong> pa ndërhyrje të vazhdueshme njerëzore – një AI që është 
    <em>jo vetëm reaktive</em>, por edhe <em>proaktive</em>.
  </p>
</body>
</html>
