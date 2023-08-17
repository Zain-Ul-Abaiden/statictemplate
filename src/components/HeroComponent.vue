<template>
    <main class="flex-auto">
        <div class="mx-auto max-w-7xl px-4 mt-16 relative">
            <div class="mx-auto max-w-2xl justify-start text-left tracking-wider">
                <h1 class="font-display text-6xl font-bold text-blue-600">
                    A design conference for the dark side.
                </h1>
                <div class="mt-6 space-y-6 font-display text-2xl text-blue-900">
                    <p>
                        The next generation of web users are tech-savvy and suspicious. They
                        know how to use dev tools, they can detect a phishing scam from a
                        mile away, and they certainly aren’t accepting any checks from
                        Western Union.
                    </p>
                    <p>
                        At DeceptiConf you’ll learn about the latest dark patterns being
                        developed to trick even the smartest visitors, and you’ll learn how
                        to deploy them without ever being detected.
                    </p>
                </div>
                <dl class="mt-16 grid grid-cols-1 gap-x-10 gap-y-6 grid-flow-col justify-start text-left">
                    <div>
                        <dt class="font-mono text-sm text-blue-600">Speakers</dt>
                        <dd class="mt-0.5 text-2xl font-semibold text-blue-900">18</dd>
                    </div>
                    <div>
                        <dt class="font-mono text-sm text-blue-600">People Attending</dt>
                        <dd class="mt-0.5 text-2xl font-semibold text-blue-900">2,091</dd>
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
            <h2 class="font-display text-5xl font-medium text-blue-600">Speakers</h2>
            <p class="mt-4 font-display text-2xl text-blue-900">
                Learn from the experts on the cutting-edge of deception at the most
                sinister companies.
            </p>
        </div>

        <div class="flex justify-between mt-32">
            <div class="flex flex-col items-start h-auto text-left ml-3">
                <div class="pl-6 border-l-2 border-slate-500">
                    <span class="text-sm leading-6 text-blue-600 font-mono font-semibold">Opening Day</span>
                    <p class="text-2xl text-blue-900 font-semibold tracking-tight mb-8">
                        April 4
                    </p>
                </div>
                <br />
                <div class="pl-6 border-l-2 border-slate-500">
                    <span class="text-sm leading-6 text-blue-600 font-mono font-semibold">Speakers & Workshops</span>
                    <p class="text-2xl text-blue-900 font-semibold tracking-tight mb-8">
                        April 5
                    </p>
                </div>
                <br />
                <div class="pl-6 border-l-2 border-slate-500">
                    <span class="text-sm leading-6 text-blue-600 font-mono font-semibold">Interviews</span>
                    <p class="text-2xl text-blue-900 font-semibold tracking-tight mb-8">
                        April 6
                    </p>
                </div>
            </div>
            <div class="grid grid-cols-3 gap-4">
                <div v-for="i in items" :key="i" class="block max-w-[18rem] rounded-lg bg-white ">
                    <div>
                        <img class="rounded-t-lg" :src="i.image" alt="" />
                    </div>

                    <div class="justify-start text-left mb-20">
                        <h3 class="mt-8 font-display text-xl font-bold tracking-tight text-slate-900">
                            {{ i.name }}
                        </h3>
                        <p class="mt-1 text-base tracking-tight text-slate-500">
                            {{ i.title }}
                        </p>
                    </div>
                </div>
            </div>
        </div>

        <div class="justify-start text-left max-w-7xl px-8 relative mt-40">
            <div class="mx-0 max-w-4xl pr-24">
                <h2 class="font-display text-4xl font-bold text-blue-600">
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

        <div class="mt-36">

            <div class="grid grid-cols-3 gap-x-8">

                <div>
                    <h3 class="text-left ml-7 text-2xl font-semibold text-blue-900">April 4</h3>
                    <p class="text-left ml-7 text-blue-900">
                        The first day of the conference is focused on dark patterns for
                        ecommerce.
                    </p>
                    <ol
                        class="mt-10 space-y-8 bg-white/60 px-10 py-14 text-center shadow-xl shadow-blue-900/5 backdrop-blur">
                        <li>
                            <h4 class="text-lg font-semibold text-blue-900">
                                Steven McHail
                            </h4>
                            <p class="mt-1 text-blue-900">
                                Not so one-time payments
                            </p>
                            <p class="mt-1 font-mono text-sm text-slate-500">9:00AM - 10:00AM PST
                            </p>
                        </li>
                        <li>
                            <div class="mx-auto mb-8 h-px w-48 bg-indigo-500/10"></div>
                            <h4 class="text-lg font-semibold text-blue-900">
                                Jaquelin Isch
                            </h4>
                            <p class="mt-1 text-blue-900">
                                The finer print
                            </p>
                            <p class="mt-1 font-mono text-sm text-slate-500">10:00AM - 11:00AM PST</p>
                        </li>
                        <li>
                            <div class="mx-auto mb-8 h-px w-48 bg-indigo-500/10"></div>
                            <h4 class="text-lg font-semibold text-blue-900">
                                Dianne Guilianelli
                            </h4>
                            <p class="mt-1 text-blue-900">
                                Post-purchase blackmail
                            </p>
                            <p class="mt-1 font-mono text-sm text-slate-500">11:00AM - 12:00PM PST
                            </p>
                        </li>
                        <li>
                            <div class="mx-auto mb-8 h-px w-48 bg-indigo-500/10"></div>
                            <h4 class="text-lg font-semibold text-blue-900">
                                Lunch
                            </h4>
                            <p class="mt-1 font-mono text-sm text-slate-500">12:00PM - 1:00PM PST
                            </p>
                        </li>
                        <li>
                            <div class="mx-auto mb-8 h-px w-48 bg-indigo-500/10"></div>
                            <h4 class="text-lg font-semibold text-blue-900">
                                Ronni Cantadore
                            </h4>
                            <p class="mt-1 text-blue-900">Buy or die</p>
                            <p class="mt-1 font-mono text-sm text-slate-500">1:00PM - 2:00PM PST
                            </p>
                        </li>
                        <li>
                            <div class="mx-auto mb-8 h-px w-48 bg-indigo-500/10"></div>
                            <h4 class="text-lg font-semibold text-blue-900">
                                Erhart Cockrin
                            </h4>
                            <p class="mt-1 text-blue-900">
                                In-person cancellation
                            </p>
                            <p class="mt-1 font-mono text-sm text-slate-500">2:00PM - 3:00PM PST
                            </p>
                        </li>
                        <li>
                            <div class="mx-auto mb-8 h-px w-48 bg-indigo-500/10"></div>
                            <h4 class="text-lg font-semibold text-blue-900">
                                Parker Johnson
                            </h4>
                            <p class="mt-1 text-blue-900">
                                The pay/cancel switcheroo
                            </p>
                            <p class="mt-1 font-mono text-sm text-slate-500">3:00PM - 4:00PM PST
                            </p>
                        </li>
                    </ol>
                </div>

                <div>
                    <h3 class="text-left ml-7 text-2xl font-semibold text-blue-900">April 5
                    </h3>
                    <p class="text-left ml-7 text-blue-900">
                        Next we spend the day talking about deceiving people with
                        technology.
                    </p>
                    <ol
                        class="mt-10 space-y-8 bg-white/60 px-10 py-14 text-center shadow-xl shadow-blue-900/5 backdrop-blur">
                        <li>
                            <h4 class="text-lg font-semibold text-blue-900">
                                Damaris Kimura
                            </h4>
                            <p class="mt-1 text-blue-900">
                                The invisible card reader
                            </p>
                            <p class="mt-1 font-mono text-sm text-slate-500">9:00AM - 10:00AM PST
                            </p>
                        </li>
                        <li>
                            <div class="mx-auto mb-8 h-px w-48 bg-indigo-500/10"></div>
                            <h4 class="text-lg font-semibold text-blue-900">
                                Ibrahim Frasch
                            </h4>
                            <p class="mt-1 text-blue-900">
                                Stealing fingerprints
                            </p>
                            <p class="mt-1 font-mono text-sm text-slate-500">10:00AM - 11:00AM PST
                            </p>
                        </li>
                        <li>
                            <div class="mx-auto mb-8 h-px w-48 bg-indigo-500/10"></div>
                            <h4 class="text-lg font-semibold text-blue-900">
                                Cathlene Burrage
                            </h4>
                            <p class="mt-1 text-blue-900">
                                Voting machines
                            </p>
                            <p class="mt-1 font-mono text-sm text-slate-500">11:00AM - 12:00PM PST
                            </p>
                        </li>
                        <li>
                            <div class="mx-auto mb-8 h-px w-48 bg-indigo-500/10"></div>
                            <h4 class="text-lg font-semibold text-blue-900">
                                Lunch
                            </h4>
                            <p class="mt-1 font-mono text-sm text-slate-500">12:00PM - 1:00PM PST
                            </p>
                        </li>
                        <li>
                            <div class="mx-auto mb-8 h-px w-48 bg-indigo-500/10"></div>
                            <h4 class="text-lg font-semibold text-blue-900">
                                Rinaldo Beynon
                            </h4>
                            <p class="mt-1 text-blue-900">
                                Blackhat SEO that works
                            </p>
                            <p class="mt-1 font-mono text-sm text-slate-500">1:00PM - 2:00PM PST
                            </p>
                        </li>
                        <li>
                            <div class="mx-auto mb-8 h-px w-48 bg-indigo-500/10"></div>
                            <h4 class="text-lg font-semibold text-blue-900">
                                Waylon Hyden
                            </h4>
                            <p class="mt-1 text-blue-900">
                                Turning your audience into a botnet
                            </p>
                            <p class="mt-1 font-mono text-sm text-slate-500">2:00PM - 3:00PM PST
                            </p>
                        </li>
                        <li>
                            <div class="mx-auto mb-8 h-px w-48 bg-indigo-500/10"></div>
                            <h4 class="text-lg font-semibold text-blue-900">
                                Giordano Sagucio
                            </h4>
                            <p class="mt-1 text-blue-900">Fly phishing</p>
                            <p class="mt-1 font-mono text-sm text-slate-500">3:00PM - 4:00PM PST
                            </p>
                        </li>
                    </ol>
                </div>

                <div>
                    <h3 class="text-left ml-7 text-2xl font-semibold text-blue-900">April 6
                    </h3>
                    <p class="text-left ml-7 mt-1.5 text-base text-blue-900">
                        We close out the event previewing new techniques that are still
                        in development.
                    </p>
                    <ol
                        class="mt-10 space-y-8 bg-white/60 px-10 py-14 text-center shadow-xl shadow-blue-900/5 backdrop-blur">
                        <li>
                            <h4 class="text-lg font-semibold text-blue-900">
                                Andrew Greene
                            </h4>
                            <p class="mt-1 text-blue-900">
                                Neuralink dark patterns
                            </p>
                            <p class="mt-1 font-mono text-sm text-slate-500">9:00AM - 10:00AM PST
                            </p>
                        </li>
                        <li>
                            <div class="mx-auto mb-8 h-px w-48 bg-indigo-500/10"></div>
                            <h4 class="text-lg font-semibold text-blue-900">
                                Heather Terry
                            </h4>
                            <p class="mt-1 text-blue-900">
                                DALL-E for passports
                            </p>
                            <p class="mt-1 font-mono text-sm text-slate-500">10:00AM - 11:00AM PST
                            </p>
                        </li>
                        <li>
                            <div class="mx-auto mb-8 h-px w-48 bg-indigo-500/10"></div>
                            <h4 class="text-lg font-semibold text-blue-900">
                                Piers Wilkins
                            </h4>
                            <p class="mt-1 text-blue-900">
                                Quantum password cracking
                            </p>
                            <p class="mt-1 font-mono text-sm text-slate-500">11:00AM - 12:00PM PST
                            </p>
                        </li>
                        <li>
                            <div class="mx-auto mb-8 h-px w-48 bg-indigo-500/10"></div>
                            <h4 class="text-lg font-semibold text-blue-900">
                                Lunch
                            </h4>
                            <p class="mt-1 font-mono text-sm text-slate-500">12:00PM - 1:00PM PST
                            </p>
                        </li>
                        <li>
                            <div class="mx-auto mb-8 h-px w-48 bg-indigo-500/10"></div>
                            <h4 class="text-lg font-semibold text-blue-900">
                                Gordon Sanderson
                            </h4>
                            <p class="mt-1 text-blue-900">
                                SkyNet is coming
                            </p>
                            <p class="mt-1 font-mono text-sm text-slate-500">1:00PM - 2:00PM PST
                            </p>
                        </li>
                        <li>
                            <div class="mx-auto mb-8 h-px w-48 bg-indigo-500/10"></div>
                            <h4 class="text-lg font-semibold text-blue-900">
                                Kimberly Parsons
                            </h4>
                            <p class="mt-1 text-blue-900">
                                Dark patterns for the metaverse
                            </p>
                            <p class="mt-1 font-mono text-sm text-slate-500">2:00PM - 3:00PM PST
                            </p>
                        </li>
                        <li>
                            <div class="mx-auto mb-8 h-px w-48 bg-indigo-500/10"></div>
                            <h4 class="text-lg font-semibold text-blue-900">
                                Richard Astley
                            </h4>
                            <p class="mt-1 text-blue-900">
                                Knowing the game and playing it
                            </p>
                            <p class="mt-1 font-mono text-sm text-slate-500">3:00PM - 4:00PM PST
                            </p>
                        </li>
                    </ol>
                </div>
            </div>

        </div>

        <div class="mt-48">
            <div>
                <h2 class="mx-auto max-w-2xl text-center font-display text-5xl font-medium text-blue-900">
                    Current sponsorships for our workshops and speakers.
                </h2>
            </div>
            <div class="mx-auto mt-20 grid max-w-max gap-x-32 gap-y-12 grid-cols-3">
                <div class="flex items-center justify-center" v-for="x in svgPics" :key="x">
                    <img :src='x' />
                </div>
            </div>
        </div>

        <div class="mt-28 mb-28">
            <div class="mx-auto max-w-7xl px-8">
                <div class="relative bg-indigo-50 py-20 rounded-3xl px-16">

                    <div class="relative mx-auto grid gap-x-32 gap-y-14 max-w-none grid-cols-2">
                        <div class="text-left">
                            <p class="font-display text-5xl font-medium text-blue-900">
                                Stay up to date
                            </p>
                            <p class="mt-4 text-lg text-blue-900">
                                Get updates on all of our events and be the first to get
                                notified when tickets go on sale.
                            </p>
                        </div>
                        <form>
                            <h3 class="text-left text-lg font-semibold text-blue-900">
                                Sign up to our newsletter ↓
                            </h3>
                            <div class="mt-5 flex rounded-3xl bg-white py-2.5 pr-2.5 shadow-xl shadow-blue-900/5 ">
                                <input type="email" required="" placeholder="Email address"
                                    class=" flex-auto bg-transparent pl-6 pr-2.5 text-base text-slate-900 placeholder:text-slate-400" />
                                <button
                                    class="inline-flex justify-center rounded-2xl bg-blue-600 p-4 text-base font-semibold text-white hover:bg-blue-500">
                                    <span class="not-sr-only">Sign up today</span>
                                </button>
                            </div>
                        </form>
                    </div>
                </div>
            </div>
        </div>

    </main>
</template>

<script>
export default {
    name: "HeroComponent",
    data() {
        return {
            items: [
                {
                    name: "Steven McHail",
                    title: "Designer at Globex Corporation",
                    image:
                        "https://keynote.tailwindui.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fsteven-mchail.4e94472e.jpg&w=640&q=75",
                },
                {
                    name: "Jaquelin Isch",
                    title: "UX Design at InGen",
                    image:
                        "https://keynote.tailwindui.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fjaquelin-isch.880e5248.jpg&w=640&q=75",
                },
                {
                    name: "Dianne Guilianelli",
                    title: "General Manager at Initech",
                    image:
                        "https://keynote.tailwindui.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fdianne-guilianelli.b4c5891f.jpg&w=640&q=75",
                },
                {
                    name: "Ronni Cantadore",
                    title: "Design Engineer at Weyland-Yutani",
                    image:
                        "https://keynote.tailwindui.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fronni-cantadore.0d04b7fe.jpg&w=640&q=75",
                },
                {
                    name: "Erhart Cockrin",
                    title: "Product Lead at Cyberdyne",
                    image:
                        "https://keynote.tailwindui.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Ferhart-cockrin.3697fef6.jpg&w=640&q=75",
                },
                {
                    name: "Parker Johnson",
                    title: "UI Designer at MomCorp",
                    image:
                        "https://keynote.tailwindui.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fparker-johnson.3f6d7276.jpg&w=640&q=75",
                },
            ],
            svgPics: [
                "https://keynote.tailwindui.com/_next/static/media/transistor.a1e38d49.svg",
                "https://keynote.tailwindui.com/_next/static/media/tuple.2f54ed03.svg",
                "https://keynote.tailwindui.com/_next/static/media/statickit.2e06fcea.svg",
                "https://keynote.tailwindui.com/_next/static/media/mirage.e12f40ad.svg",
                "https://keynote.tailwindui.com/_next/static/media/laravel.6faebf7c.svg",
                "https://keynote.tailwindui.com/_next/static/media/statamic.923101b6.svg"
            ]
        };
    },
};
</script>

<style scoped></style>
