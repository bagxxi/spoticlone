<script lang="ts">
    const currentTime = new Date()
    const currentHour = currentTime.getHours()

    let greeting = ""

    if (currentHour < 12 && currentHour > 5) {
        greeting = "Buen día, viteh"
    } else if (currentHour > 12 && currentHour < 20 ) {
        greeting = "Buenas tardes, viteh"
    } else {
        greeting = "Buenas noches, viteh"
    }
</script>

<h1 class="text-3xl font-bold">{greeting}</h1>