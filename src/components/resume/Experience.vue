<template>
  <div>
    <h2 class="experience">Experience</h2>
    <div class="card">
      <h3 class="card-title">Software Engineer, Raytheon</h3>
      <div class="card-body">
      <h5>Gloucester — October 2018 - October 2019</h5>
      <p>At Raytheon I worked in a team that utilised AWS to produce QuickSight visualisations allowing the client to analyse their data. To most effectively present the data, we used Athena to analyse and understand the S3 data we had been given. Once we had understood the data, we ran a Glue crawler on it to produce tables that allowed us to view it on Athena and more effectively interact with QuickSight, opposed to using purely CSV data. We performed Further work on the data which consisted of using Python’s Sci-Kit Learn library on Jupyter Notebooks to explore the data more thoroughly.</p>
      <br>
      <p>I joined a different team in Raytheon in March. In this team we were tasked ingesting big data and making it available to multiple end users. We used Azure as our cloud service provider and created an Elasticsearch cluster capable of handling an ingest rate of 150k documents per second. One of the key responsibilities I took on was to manage the cluster and spent my time maintaining, optimising and reducing costs. I eventually became the ‘Guru’ of the cluster and the team would consult with me about the best course of action to take when making changes. We exposed this data up using Azures APIM and Functions following the best security practices.</p>
      <ul>
        <li>Java, Python, Javascript</li>
        <li>React</li>
        <li>Jenkins, Github, Postman</li>
        <li>Elasticsearch</li>
        <li>Docker, Kubernetes</li>
      </ul>
    </div>
    <div>
      <h3 class="card-title">Software Developer, Ian Williams</h3>
      <div class="card-body">
      <h5>Newport — June 2017 - October 2018</h5>
      <p>At Ian Williams I worked in a team which allowed clients to place orders in our system in a format they preferred, such as PDF or XML. It would then be our job to extract the data to allow it to integrate with our systems. This model was chosen as it reduced the complexity for the client to integrate with our systems. As a side project while working there, I made an error tracking web application which incorporated bootstrap on the frontend, a Java-based RESTful web service and a MSSQL backend. This application informed users on how to resolve errors they may come across through day-to-day use. If any new errors were found, it also allows users to submit new errors to the system and once a fix was found, allow it to be updated for future reference.</p>
      <ul>
        <li>Java, Javascript</li>
        <li>React, AngularJS, Spring</li>
        <li>Jenkins, SVN</li>
        <li>SQL</li>
      </ul>
    </div>
    </div>
    <div>
      <h3 class="card-title">Projects</h3>
      <div class="card-body">
      <p>In my spare time, I like to improve my abilities. I have done this through contributing to open-source projects and also my own. I have been contributing to a project, called Nanotify. This service notifies users of any incoming or pending transactions using the Nano cryptocurrency coin by sending users an email. The project has been extended to mobile devices now, which has been written in React Native to allow for maximal cross platform usage. </p>
    </div>
    </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Experience'
}
</script>

<style scoped>
@media screen and (max-width: 767px) {
  h2 {
      text-align: center;
      font-size: 1.6rem;
  }
  h3 {
      font-size: 1.2rem;
  }
  h5 {
      font-size: 1rem;
  }
  .card-body {
    padding-left: 0px;
    padding-right: 0px;
  }
  .card {
    padding-left: 0px;
    padding-right: 0px;
  }
  h2.experience {
    text-align: center;
  }
  ul,li {
    list-style:none;
    padding-inline-start: 0px;
  }
  li {
    list-style:none;
    padding-inline-start: 10px;
  }
  li:before {
    content:'\00b7';
    font-size: 1.2rem;
    padding-right: 10px;
  }
}
.experience {
  text-align: left;
}

</style>
