<svelte:head>
    <title>{status ?? '에러'} 에러 - 포트폴리오</title>
</svelte:head>

<div class="flex flex-col items-center justify-center min-h-[70vh] text-center text-red-700">
    <div class="text-7xl font-bold mb-4">{status}</div>
    <div class="text-xl mb-8">
        {error?.message ?? '알 수 없는 에러가 발생했습니다.'}
    </div>
    <a href="/" class="text-blue-600 underline text-base hover:text-blue-800 transition-colors">
        홈으로 돌아가기
    </a>
</div>
