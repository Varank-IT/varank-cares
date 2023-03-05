<template>
    <div style="overflow-x: auto;" id="schedule">
        <SectionLabel label="Organizasyon Takvimi" />
        <table>
            <tr>
                <th style="font-size: 20px;">Gün 1</th>
                <th style="font-size: 20px;"></th>
            </tr>
            <tr>
                <td>08.30-09.00</td>
                <td>Açılış</td>
            </tr>
            <tr>
                <td>09.00-09.30</td>
                <td>Konuşmacılar</td>
            </tr>
            <tr>
                <td>09.30-10.00</td>
                <td>Ara/Kahvaltı</td>
            </tr>
            <tr>
                <td>10.00-11.00</td>
                <td>Sunum Komite</td>
            </tr>
            <tr>
                <td>11.00-11.15</td>
                <td>Ara ve Workshop Dağıtımı</td>
            </tr>
            <tr>
                <td>11.15-12.00</td>
                <td>Workshop</td>
            </tr>
            <tr>
                <td>12.00-12.10</td>
                <td>Ara</td>
            </tr>
            <tr>
                <td>12.10-13.00</td>
                <td>Konuşmacılar</td>
            </tr>
            <tr>
                <td>13.00-14.30</td>
                <td>Öğlen Arası</td>
            </tr>
            <tr>
                <td>14.30-15.30</td>
                <td>Dergi Komite</td>
            </tr>
            <tr>
                <td>15.30-15.45</td>
                <td>Ara</td>
            </tr>
            <tr>
                <td>15.45-16.15</td>
                <td>Konuşmacılar</td>
            </tr>
            <tr>
                <td>16.15-16.30</td>
                <td>Ara</td>
            </tr>
            <tr>
                <td>16.30-17.00</td>
                <td>Dergi Komite - Kapanış</td>
            </tr>
            <tr>
                <th style="font-size: 20px;">Gün 2</th>
                <th style="font-size: 20px;"></th>
            </tr>
            <tr>
                <td>09.00-09.30</td>
                <td>Açılış</td>
            </tr>
            <tr>
                <td>09.30-11.00</td>
                <td>Sunum Komite</td>
            </tr>
            <tr>
                <td>11.00-11.10</td>
                <td>Ara</td>
            </tr>
            <tr>
                <td>11.10-12.10</td>
                <td>Sunum Komite</td>
            </tr>
            <tr>
                <td>12.10-12.20</td>
                <td>Ara</td>
            </tr>
            <tr>
                <td>12.20-13.20</td>
                <td>Sunum</td>
            </tr>
            <tr>
                <td>13.20-14.50</td>
                <td>Öğle Arası</td>
            </tr>
            <tr>
                <td>14.50-15.50</td>
                <td>Sunum</td>
            </tr>
            <tr>
                <td>15.50-17.30</td>
                <td>Etkinlikler ve Kapanış</td>
            </tr>
        </table>
</div>
</template>

<script>
import SectionLabel from './SectionLabel.vue'

export default {
    name: 'Day1Table',
    components: {
        SectionLabel
    }
}
</script>

<style scoped>
div {
    padding: 2vh 12vw;
}

table {
    border-collapse: collapse;
    width: 100%;
    padding-left: 10vh;
    padding-right: 10vh;
    padding-top: 10vh;
    padding-bottom: 10vh;
}

th,

td {
    text-align: left;
    padding: 8px;
}

tr:nth-child(even) {
    background-color: #f2f2f2;
}
</style>