<script>
export default {
  data() {
    return {
      experiences: [
        {
          year: "Oct 2024 - Present",
          jobs: "Student Staff - UPT Lab",
          company: "Universitas Amikom",
          location: "Yogyakarta",
          description: [
            "Involved in the development or maintenance of systems used in the laboratory if needed, for example managing local networks or updating software and hardware systems in the device inventory system.",
          ],
        },
        {
          year: "Mar 2024 - Aug 2024",
          jobs: "Asisten Praktikum - Keamanan Data dan Informasi",
          company: "Universitas Amikom",
          location: "Yogyakarta",
          description: [
            "Contribute in helping lecturers to deliver material related to Python using Google Collaboration, coordinating classes to smooth the practical process in the laboratory and providing grades to students regarding assignments given by lecturers",
          ],
        },
        {
          year: "Mar 2024 - Aug 2024",
          jobs: "Asisten Praktikum - Sistem Operasi",
          company: "Universitas Amikom",
          location: "Yogyakarta",
          description: [
            "Contribute in helping lecturers to deliver Ubuntu Linux material and commands on the operating system, coordinating classes for smooth practicums in the laboratory and providing grades to students regarding assignments given by lecturers.",
          ],
        },
        {
          year: "Mar 2024 - Aug 2024",
          jobs: "Asisten Praktikum - Aplikasi SIG Mobile",
          company: "Universitas Amikom",
          location: "Yogyakarta",
          description: [
            "Contribute in helping lecturers to deliver material related to hardware & software configuration, switches and routers, Coordinate classes to smooth the practical process in the laboratory and provide grades to students regarding assignments given by lecturers.",
          ],
        },
        {
          year: "Feb 2024 - Jun 2024",
          jobs: "STUDI INDEPENDEN MSIB",
          company: "GAMELAB.ID",
          location: "Remote",
          description: [
            "Program Studi Independen Bersertifikat  Front-End Web Development ",
          ],
        },
        {
          year: "Sep 2023 - Jan 2024",
          jobs: "Asisten Praktikum - Sistem Basis Data",
          company: "Universitas Amikom",
          location: "Yogyakarta",
          description: [
            "Contribute in helping lecturers to deliver material related to hardware & software configuration, switches and routers, Coordinate classes to smooth the practical process in the laboratory and provide grades to students regarding assignments given by lecturers.",
          ],
        },
        {
          year: "Sep 2023 - Jan 2024",
          jobs: "Asisten Praktikum - Mikrokontroler",
          company: "Universitas Amikom",
          location: "Yogyakarta",
          description: [
            "Contribute in helping lecturers to deliver material related to hardware & software configuration, switches and routers, Coordinate classes to smooth the practical process in the laboratory and provide grades to students regarding assignments given by lecturers.",
          ],
        },
        {
          year: "Sep 2023 - Jan 2024",
          jobs: "Asisten Praktikum - Jaringan Komputer 1",
          company: "Universitas Amikom",
          location: "Yogyakarta",
          description: [
            "Contribute in helping lecturers to deliver material related to hardware & software configuration, switches and routers, Coordinate classes to smooth the practical process in the laboratory and provide grades to students regarding assignments given by lecturers.",
          ],
        },
        {
          year: "Mar 2023 - Jul 2023",
          jobs: "Asisten Praktikum - Sistem Operasi",
          company: "Universitas Amikom",
          location: "Yogyakarta",
          description: [
            "Contribute in helping lecturers to deliver material related to hardware & software configuration, switches and routers, Coordinate classes to smooth the practical process in the laboratory and provide grades to students regarding assignments given by lecturers.",
          ],
        },
        {
          year: "Mar 2023 - Jul 2023",
          jobs: "Asisten Praktikum - Jaringan Komputer 1",
          company: "Universitas Amikom",
          location: "Yogyakarta",
          description: [
            "Contribute in helping lecturers to deliver material related to hardware & software configuration, switches and routers, Coordinate classes to smooth the practical process in the laboratory and provide grades to students regarding assignments given by lecturers.",
          ],
        },
      ],
    };
  },
};
</script>

<template>
  <section>
    <div class="d-flex align-items-center justify-content-between mb-0">
      <h2 class="text-primary fw-bolder mb-0">Experience</h2>
      <!--      <a class="btn btn-primary px-4 py-3" href="#!">-->
      <!--        <div class="d-inline-block bi bi-download me-2"></div>-->
      <!--        Download Resume-->
      <!--      </a>-->
    </div>

    <div
      v-for="experience of experiences"
      :key="'experience-index-' + experience.company"
      class="card shadow border-0 rounded-4 mb-0"
    >
      <div class="card-body px-3 px-md-5 py-5">
        <div class="row align-items-center gx-5">
          <div class="col text-center text-lg-start mb-4 mb-lg-0">
            <div class="p-4 rounded-4">
              <div class="text-primary fw-bolder mb-2">
                {{ experience.year }}
              </div>
              <div class="small fw-bolder">{{ experience.jobs }}</div>
              <div class="small text-muted">{{ experience.company }}</div>
              <div class="small text-muted">{{ experience.location }}</div>
            </div>
          </div>
          <div class="col-lg-8">
            <div>
              <ul class="mb-0">
                <ul>
                  <li v-for="desc in experience.description" :key="desc">
                    {{ desc }}
                  </li>
                </ul>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped></style>
