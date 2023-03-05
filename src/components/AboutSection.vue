<template>
    <section class="bio-section">
        <div id="bio">
            <SectionLabel label="Etkinlik Hakkında" />
            <p>
                VarankCares, liseli öğrencilerin bir araya gelip toplumu olumsuz etkileyen ve fikir ayrılıklarına sebep olan
                bazı dünya sorunlarına çözüm üretmelerini sağlamayı amaçlayan iki günlük bir farkındalık kampıdır. Bu iki
                gün boyunca katılımcıların ekip olarak
                <b>Irkçılık, Kadın ve Erkek Eşitliği, Çocuk Hakları, Siber Suçlar, Savaşlar, Eğitimde Fırsat Eşitliği</b> ve
                <b> Hayvan Hakları</b> konuları üzerinde duracaktır.
                Katılımcılarımız ilk olarak konularıyla alakalı uzman kişilerin yapacakları konuşmaları dinledikten sonra
                bunlardan ilham alarak kendi konuşmalarını hazırlayacaklardır. Daha sonrasında buldukları fikir ve çözümleri
                içeren ve tasarımlarını da kendileri yapacakları bir dergi oluşturacaklardır. Organizasyon ekibi olarak
                amacımız katılımcılarımız özgürce fikirlerini ifade edip çözüm üretme, fikir yürütme, özgüven gibi
                becerilerini geliştirirken aynı zamanda sosyal çevrelerini genişletip eğlenceli vakit geçirmelerini
                sağlamaktır. Dünyamızdaki sorunları görmezden gelmeyi reddediyor ve bunlara karşı gençler olarak el ele
                verip çözüm üretmek istiyoruz.
            </p>
        </div>
</section>
</template>

<script>
import SectionLabel from './SectionLabel.vue'

export default {
    name: 'AboutSection',
    components: {
        SectionLabel
    }
}
</script>

<style scoped>
#bio {
    font-size: 20px;
    margin-left: 12%;
    margin-right: 12%;
    margin-top: 50px;
    word-spacing: normal;
    text-align: center;
}

.sub-h {
    font-size: 30px;
}
</style>
