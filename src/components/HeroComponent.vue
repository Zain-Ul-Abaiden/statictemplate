<template>
    <main class="flex-auto">
        <div class="mx-auto max-w-7xl px-4 mt-16 relative">
            <div class="mx-auto max-w-2xl justify-start text-left tracking-wider">
                <h1 class="font-display text-6xl font-bold text-blue-600">A design conference for the dark side.</h1>
                <div class="mt-6 space-y-6 font-display text-2xl text-blue-900">
                    <p>The next generation of web users are tech-savvy and suspicious. They know how to use dev tools, they
                        can detect a phishing scam from a mile away, and they certainly aren’t accepting any checks from
                        Western Union.</p>
                    <p>At DeceptiConf you’ll learn about the latest dark patterns being developed to trick even the smartest
                        visitors, and you’ll learn how to deploy them without ever being detected.</p>
                </div>
                <dl class="mt-16 grid grid-cols-1 gap-x-10 gap-y-6 grid-flow-col justify-start text-left">
                    <div>
                        <dt class="font-mono text-sm text-blue-600">Speakers</dt>
                        <dd class="mt-0.5 text-2xl font-semibold text-blue-900">
                            18
                        </dd>
                    </div>
                    <div>
                        <dt class="font-mono text-sm text-blue-600">People Attending</dt>
                        <dd class="mt-0.5 text-2xl font-semibold text-blue-900">
                            2,091
                        </dd>
                    </div>
                    <div>
                        <dt class="font-mono text-sm text-blue-600">Venue</dt>
                        <dd class="mt-0.5 text-2xl font-semibold text-blue-900">
                            Staples Center
                        </dd>
                    </div>
                    <div>
                        <dt class="font-mono text-sm text-blue-600">Location</dt>
                        <dd class="mt-0.5 text-2xl font-semibold text-blue-900">
                            Los Angeles
                        </dd>
                    </div>
                </dl>
            </div>
        </div>

        <div class="mx-8 max-w-2xl mt-40 justify-start text-left">
            <h2 class="font-display text-5xl font-medium  text-blue-600">
                Speakers
            </h2>
            <p class="mt-4 font-display text-2xl text-blue-900">
                Learn from the experts on the cutting-edge of deception at the most
                sinister companies.
            </p>
        </div>

        <div class="flex justify-between">
            <div class="flex flex-col items-start h-auto text-left" >
        <div class="pl-6 border-l-2 border-double border-slate-500">
          <span class="text-sm leading-6 text-blue-600 font-mono font-semibold ">Opening Day</span>
          <p class="text-2xl text-blue-900 font-semibold tracking-tight mb-8" >April 4</p>
        </div>
        <br>
        <div class="pl-6 border-l-2 border-double border-slate-500" >
          <span class="text-sm leading-6 text-blue-600 font-mono font-semibold ">Speakers & Workshops</span>
          <p class="text-2xl text-blue-900 font-semibold tracking-tight mb-8" >April 5</p>
        </div>
        <br>
        <div class="pl-6 border-l-2 border-double border-slate-500"  >
          <span class="text-sm leading-6 text-blue-600 font-mono font-semibold ">Interviews</span>
          <p class="text-2xl text-blue-900 font-semibold tracking-tight mb-8" >April 6</p>
        </div>
      </div>








            <div v-for="i in items" :key="i"
                class="block max-w-[18rem] rounded-lg bg-white shadow-[0_2px_15px_-3px_rgba(0,0,0,0.07),0_10px_20px_-2px_rgba(0,0,0,0.04)] dark:bg-neutral-700">
                <div class="relative overflow-hidden bg-cover bg-no-repeat">
                    <img class="rounded-t-lg" :src="i.image" alt="" />
                </div>

                <div class="p-6">
                    <h3 class="mt-8 font-display text-xl font-bold tracking-tight text-slate-900">
                        {{ i.name }}
                    </h3>
                    <p class="mt-1 text-base tracking-tight text-slate-500">
                        {{ i.title }}
                    </p>
                </div>
            </div>
        </div>


        <div class="justify-start text-left max-w-7xl px-8 relative mt-40">
            <div class="mx-0 max-w-4xl pr-24">
                <h2 class="font-display text-4xl font-medium  text-blue-600 ">
                    Our three day schedule is jam-packed with brilliant, creative, evil
                    geniuses.
                </h2>
                <p class="mt-4 font-display text-2xl text-blue-900">
                    The worst people in our industry giving the best talks you’ve ever
                    seen. Nothing will be recorded and every attendee has to sign an NDA
                    to watch the talks.
                </p>
            </div>
        </div>

        <div class="grid grid-cols-3 mt-20 py-4">
            <div class="relative w-3/4 flex-none pr-4 ">
                <h3 class="text-2xl font-semibold tracking-tight text-blue-900">April 4</h3>
                <p class="mt-1.5 text-base text-blue-900">
                    The first day of the conference is focused on dark patterns
                    for ecommerce.
                </p>
            </div>
            <div class="relative w-3/4 flex-none pr-4 ">
                <h3 class="text-2xl font-semibold tracking-tight text-blue-900">April 5</h3>
                <p class="mt-1.5 text-base text-blue-900">
                    Next we spend the day talking about deceiving people with technology.
                </p>
            </div>
            <div class="relative w-3/4 flex-none pr-4 ">
                <h3 class="text-2xl font-semibold tracking-tight text-blue-900">April 6</h3>
                <p class="mt-1.5 text-base text-blue-900">
                    We close out the event previewing new techniques that are still in development.
                </p>
            </div>

        </div>
    </main>
</template>

<script>
export default {
    name: 'HeroComponent',
    data() {
        return {
            items: [
                { name: 'Steven McHail', title: 'Designer at Globex Corporation', image: "https://keynote.tailwindui.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fsteven-mchail.4e94472e.jpg&w=640&q=75" },
                { name: 'Jaquelin Isch', title: 'UX Design at InGen', image: "https://keynote.tailwindui.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fjaquelin-isch.880e5248.jpg&w=640&q=75" },
                { name: 'Dianne Guilianelli', title: 'General Manager at Initech', image: "https://keynote.tailwindui.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fdianne-guilianelli.b4c5891f.jpg&w=640&q=75" },
                { name: 'Ronni Cantadore', title: 'Design Engineer at Weyland-Yutani', image: "https://keynote.tailwindui.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fronni-cantadore.0d04b7fe.jpg&w=640&q=75" },
                { name: 'Erhart Cockrin', title: 'Product Lead at Cyberdyne', image: "https://keynote.tailwindui.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Ferhart-cockrin.3697fef6.jpg&w=640&q=75" },
                { name: 'Parker Johnson', title: 'UI Designer at MomCorp', image: "https://keynote.tailwindui.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fparker-johnson.3f6d7276.jpg&w=640&q=75" },
            ]
        }
    }
}
</script>

<style scoped></style>