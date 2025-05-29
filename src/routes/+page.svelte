<script>
    // 예시 데이터 (필요시 수정)
    const news = [
        { title: "2024학년도 신입생 모집", date: "2024-06-01", link: "#" },
        { title: "스마트모빌리티 산학협력 MOU 체결", date: "2024-05-20", link: "#" },
        { title: "자율주행 프로젝트 발표회", date: "2024-05-10", link: "#" }
    ];
</script>

<div class="bg-gradient-to-br from-blue-500 to-white text-white py-16 px-4 text-center rounded-b-3xl">
    <img src="/logo.png" alt="스마트모빌리티학과 로고" class="w-24 mx-auto mb-4" />
    <h1 class="text-3xl font-bold mb-2">평택대학교 스마트모빌리티학과</h1>
    <p class="text-lg font-medium text-white/90">
        미래 모빌리티 산업을 선도할 창의적 인재 양성<br />
        자율주행, 전기차, IoT, AI 등 첨단 기술을 배우는 곳
    </p>
</div>

<section class="max-w-2xl mx-auto my-8 p-6 bg-gray-50 rounded-xl shadow">
    <h2 class="text-xl font-semibold mb-3 text-blue-600">학과 소개</h2>
    <p class="text-gray-700 leading-relaxed">
        스마트모빌리티학과는 자율주행, 전기차, 인공지능, 사물인터넷 등<br />
        미래 모빌리티 산업을 이끌어갈 융합형 인재를 양성합니다.<br />
        실무 중심의 커리큘럼과 산학협력을 통해 현장 맞춤형 교육을 제공합니다.
    </p>
</section>

<section class="max-w-2xl mx-auto my-8 p-6 bg-gray-50 rounded-xl shadow">
    <h2 class="text-xl font-semibold mb-3 text-blue-600">공지사항</h2>
    <ul class="divide-y divide-gray-200">
        {#each news as item}
            <li class="py-3 flex items-center justify-between">
                <a class="font-bold text-blue-500 hover:underline" href={item.link}>{item.title}</a>
                <span class="text-sm text-gray-500 ml-4">{item.date}</span>
            </li>
        {/each}
    </ul>
</section>

<section class="max-w-2xl mx-auto my-8 p-6 bg-gray-50 rounded-xl shadow">
    <h2 class="text-xl font-semibold mb-3 text-blue-600">문의</h2>
    <p class="text-gray-700">
        학과 사무실: 031-123-4567<br />
        이메일: smartmobility@ptu.ac.kr
    </p>
</section>
