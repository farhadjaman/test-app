<script>
import { FFmpeg } from '@ffmpeg/ffmpeg';
import { toBlobURL } from '@ffmpeg/util';
import loadFfmpeg from '@/utils/loadFfmpeg';
let ffmpegRef;

const load = async () => {
    const ffmpeg_response = await loadFfmpeg();
    ffmpegRef = ffmpeg_response;
    console.log('ffmpeg loaded');
};

console.log('loading ffmpeg');

await load();
</script>

<template>
    <div>home</div>
</template>
