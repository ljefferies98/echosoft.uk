<template>
  <div>
    <div class="card" v-bind:key='name' v-for="(skill, name) in skills">
    <h4 class="card-title text-center">{{name}}</h4>
    <b-row class="card-body">
      <b-col cols="12" v-bind:key='item.name' v-for="item in skill">
        <p>{{item.name}}</p>
        <b-progress :value='item.percentage' :max='100'></b-progress>
      </b-col>
    </b-row>
    </div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      skills:
        {
          'Java': [
            {
              name: 'Java',
              percentage: 85
            },
            {
              name: 'Spring Boot',
              percentage: 70
            },
            {
              name: 'Spring Framework',
              percentage: 80
            },
            {
              name: 'Spark Java',
              percentage: 75
            },
            {
              name: 'Junit 4',
              percentage: 85
            },
            {
              name: 'Mockito',
              percentage: 85
            }
          ],
          'Python': [
            {
              name: 'Python',
              percentage: 75
            },
            {
              name: 'Flask',
              percentage: 75
            },
            {
              name: 'pytest',
              percentage: 70
            }
          ],
          'Web': [
            {
              name: 'React',
              percentage: 75
            },
            {
              name: 'VueJS',
              percentage: 70
            },
            {
              name: 'Bootstrap',
              percentage: 80
            },
            {
              name: 'Angular',
              percentage: 70
            },
            {
              name: 'REST',
              percentage: 85
            }
          ],
          'Database': [
            {
              name: 'MongoDB',
              percentage: 75
            },
            {
              name: 'DynamoDB',
              percentage: 80
            },
            {
              name: 'ElasticSearch',
              percentage: 85
            }
          ],
          'Devops': [
            {
              name: 'Kubernetes',
              percentage: 80
            },
            {
              name: 'Docker',
              percentage: 80
            },
            {
              name: 'Jenkins',
              percentage: 80
            },
            {
              name: 'Terraform',
              percentage: 75
            }
          ],
          'Cloud': [
            {
              name: 'AWS',
              percentage: 75
            },
            {
              name: 'Azure',
              percentage: 80
            }
          ]
        }
    }
  }
}
</script>

<!-- Add 'scoped' attribute to limit CSS to this component only -->
<style scoped>
@media screen and (max-width: 767px) {
  h4 {
      font-size: 1.4rem;
  }
  .card {
    padding: 0px;
  }
}

.card {
  background-color: #00000000;
  padding-top: 15px;
}

.card-body {
  padding: 0px;
}

p {
  font-family: 'Darker Grotesque','Helvetica Neue', Helvetica, Arial, sans-serif, cursive !important;
  margin-bottom: 0px;
}
</style>
