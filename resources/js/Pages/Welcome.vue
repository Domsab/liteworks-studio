<template>
    <Head title="Welcome" />
        <GuestLayout>
        <div class="px-6 lg:px-8 bg-gray-900">
            <div class="mx-auto max-w-2xl py-32 sm:py-48 lg:py-56">
            <div class="hidden sm:mb-8 sm:flex sm:justify-center">
            <div class="relative rounded-full py-1 px-3 text-sm leading-6 text-gray-400 ring-1 ring-white/10 hover:ring-white/20">
                Announcing our next round of funding. <a href="#" class="font-semibold text-white"><span class="absolute inset-0" aria-hidden="true" />Read more <span aria-hidden="true">&rarr;</span></a>
            </div>
            </div>
            <div class="text-center">
            <h1 class="text-4xl font-bold tracking-tight text-white sm:text-6xl">Services to enrich your online business</h1>
            <p class="mt-6 text-lg leading-8 text-gray-300">Anim aute id magna aliqua ad ad non deserunt sunt. Qui irure qui lorem cupidatat commodo. Elit sunt amet fugiat veniam occaecat fugiat aliqua.</p>
            <div class="mt-10 flex items-center justify-center gap-x-6">
                <a href="#" class="rounded-md bg-indigo-500 px-3.5 py-2.5 text-sm font-semibold text-white shadow-sm hover:bg-indigo-400 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-400">Get started</a>
                <a href="#" class="text-sm font-semibold leading-6 text-white">Learn more <span aria-hidden="true">→</span></a>
            </div>
            </div>
        </div>
        </div>

        <div class="bg-white py-24 sm:py-32">
    <div class="mx-auto max-w-7xl px-6 lg:px-8">
      <div class="mx-auto max-w-2xl lg:text-center">
        <h2 class="text-base font-semibold leading-7 text-indigo-600">Deploy faster</h2>
        <p class="mt-2 text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl">Everything you need to deploy your app</p>
        <p class="mt-6 text-lg leading-8 text-gray-600">Quis tellus eget adipiscing convallis sit sit eget aliquet quis. Suspendisse eget egestas a elementum pulvinar et feugiat blandit at. In mi viverra elit nunc.</p>
      </div>
      <div class="mx-auto mt-16 max-w-2xl sm:mt-20 lg:mt-24 lg:max-w-none">
        <dl class="grid max-w-xl grid-cols-1 gap-x-8 gap-y-16 lg:max-w-none lg:grid-cols-2">
          <div v-for="feature in features" :key="feature.name" class="flex flex-col">
            <dt class="flex items-center gap-x-3 text-base font-semibold leading-7 text-gray-900">
              <component :is="feature.icon" class="h-5 w-5 flex-none text-indigo-600" aria-hidden="true" />
              {{ feature.name }}
            </dt>
            <dd class="mt-4 flex flex-auto flex-col text-base leading-7 text-gray-600">
              <p class="flex-auto">{{ feature.description }}</p>
              <p class="mt-6">
                <a :href="feature.href" class="text-sm font-semibold leading-6 text-indigo-600">Learn more <span aria-hidden="true">→</span></a>
              </p>
            </dd>
          </div>
        </dl>
      </div>
    </div>
  </div>
        <PackageDetailRight/>

        <PackageDetailLeft/>

        <PackageDetailRight/>
        <div class="relative isolate bg-white">
    <div class="mx-auto grid max-w-7xl grid-cols-1 lg:grid-cols-2">
      <div class="relative px-6 pt-24 pb-20 sm:pt-32 lg:static lg:py-48 lg:px-8">
        <div class="mx-auto max-w-xl lg:mx-0 lg:max-w-lg">
          <div class="absolute inset-y-0 left-0 -z-10 w-full overflow-hidden bg-gray-100 ring-1 ring-gray-900/10 lg:w-1/2">
            <svg class="absolute inset-0 h-full w-full stroke-gray-200 [mask-image:radial-gradient(100%_100%_at_top_right,white,transparent)]" aria-hidden="true">
              <defs>
                <pattern id="83fd4e5a-9d52-42fc-97b6-718e5d7ee527" width="200" height="200" x="100%" y="-1" patternUnits="userSpaceOnUse">
                  <path d="M130 200V.5M.5 .5H200" fill="none" />
                </pattern>
              </defs>
              <rect width="100%" height="100%" stroke-width="0" fill="white" />
              <svg x="100%" y="-1" class="overflow-visible fill-gray-50">
                <path d="M-470.5 0h201v201h-201Z" stroke-width="0" />
              </svg>
              <rect width="100%" height="100%" stroke-width="0" fill="url(#83fd4e5a-9d52-42fc-97b6-718e5d7ee527)" />
            </svg>
          </div>
          <h2 class="text-3xl font-bold tracking-tight text-gray-900">Get in touch</h2>
          <p class="mt-6 text-lg leading-8 text-gray-600">Proin volutpat consequat porttitor cras nullam gravida at. Orci molestie a eu arcu. Sed ut tincidunt integer elementum id sem. Arcu sed malesuada et magna.</p>
          <dl class="mt-10 space-y-4 text-base leading-7 text-gray-600">
            <div class="flex gap-x-4">
              <dt class="flex-none">
                <span class="sr-only">Telephone</span>
                <BuildingOffice2Icon class="h-7 w-6 text-gray-400" aria-hidden="true" />
              </dt>
              <dd>545 Mavis Island<br />Chicago, IL 99191</dd>
            </div>
            <div class="flex gap-x-4">
              <dt class="flex-none">
                <span class="sr-only">Telephone</span>
                <PhoneIcon class="h-7 w-6 text-gray-400" aria-hidden="true" />
              </dt>
              <dd><a class="hover:text-gray-900" href="tel:+1 (555) 234-5678">+1 (555) 234-5678</a></dd>
            </div>
            <div class="flex gap-x-4">
              <dt class="flex-none">
                <span class="sr-only">Telephone</span>
                <EnvelopeIcon class="h-7 w-6 text-gray-400" aria-hidden="true" />
              </dt>
              <dd><a class="hover:text-gray-900" href="mailto:hello@example.com">hello@example.com</a></dd>
            </div>
          </dl>
        </div>
      </div>
      <form action="#" method="POST" class="px-6 pb-24 pt-20 sm:pb-32 lg:py-48 lg:px-8">
        <div class="mx-auto max-w-xl lg:mr-0 lg:max-w-lg">
          <div class="grid grid-cols-1 gap-y-6 gap-x-8 sm:grid-cols-2">
            <div>
              <label for="first-name" class="block text-sm font-semibold leading-6 text-gray-900">First name</label>
              <div class="mt-2.5">
                <input type="text" name="first-name" id="first-name" autocomplete="given-name" class="block w-full rounded-md border-0 py-2 px-3.5 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:text-sm sm:leading-6" />
              </div>
            </div>
            <div>
              <label for="last-name" class="block text-sm font-semibold leading-6 text-gray-900">Last name</label>
              <div class="mt-2.5">
                <input type="text" name="last-name" id="last-name" autocomplete="family-name" class="block w-full rounded-md border-0 py-2 px-3.5 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:text-sm sm:leading-6" />
              </div>
            </div>
            <div class="sm:col-span-2">
              <label for="email" class="block text-sm font-semibold leading-6 text-gray-900">Email</label>
              <div class="mt-2.5">
                <input type="email" name="email" id="email" autocomplete="email" class="block w-full rounded-md border-0 py-2 px-3.5 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:text-sm sm:leading-6" />
              </div>
            </div>
            <div class="sm:col-span-2">
              <label for="phone-number" class="block text-sm font-semibold leading-6 text-gray-900">Phone number</label>
              <div class="mt-2.5">
                <input type="tel" name="phone-number" id="phone-number" autocomplete="tel" class="block w-full rounded-md border-0 py-2 px-3.5 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:text-sm sm:leading-6" />
              </div>
            </div>
            <div class="sm:col-span-2">
              <label for="message" class="block text-sm font-semibold leading-6 text-gray-900">Message</label>
              <div class="mt-2.5">
                <textarea name="message" id="message" rows="4" class="block w-full rounded-md border-0 py-2 px-3.5 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:text-sm sm:leading-6" />
              </div>
            </div>
          </div>
          <div class="mt-8 flex justify-end">
            <button type="submit" class="rounded-md bg-indigo-600 px-3.5 py-2.5 text-center text-sm font-semibold text-white shadow-sm hover:bg-indigo-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-600">Send message</button>
          </div>
        </div>
      </form>
    </div>
  </div>
    </GuestLayout>
</template>

<script setup>
import PackageDetailRight from '@/Components/PackageDetailRight.vue';
import PackageDetailLeft from '@/Components/PackageDetailLeft.vue';
import GuestLayout from '@/Layouts/GuestLayout.vue';
import { Head } from '@inertiajs/vue3';
import { ArrowPathIcon, CloudArrowUpIcon, LockClosedIcon } from '@heroicons/vue/20/solid'
import { BuildingOffice2Icon, EnvelopeIcon, PhoneIcon } from '@heroicons/vue/24/outline'


const features = [
  {
    name: 'Professional Laravel Development',
    description:
      'Commodo nec sagittis tortor mauris sed. Turpis tortor quis scelerisque diam id accumsan nullam tempus. Pulvinar etiam lacus volutpat eu. Phasellus praesent ligula sit faucibus.',
    href: '#',
    icon: CloudArrowUpIcon,
  },
  {
    name: 'Rich Interactive Frontends powered by Vuejs',
    description:
      'Pellentesque enim a commodo malesuada turpis eleifend risus. Facilisis donec placerat sapien consequat tempor fermentum nibh.',
    href: '#',
    icon: LockClosedIcon,
  },
]

defineProps({
    canLogin: Boolean,
    canRegister: Boolean,
    laravelVersion: String,
    phpVersion: String,
});
</script>

<style>
.bg-dots-darker {
    background-image: url("data:image/svg+xml,%3Csvg width='30' height='30' viewBox='0 0 30 30' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath d='M1.22676 0C1.91374 0 2.45351 0.539773 2.45351 1.22676C2.45351 1.91374 1.91374 2.45351 1.22676 2.45351C0.539773 2.45351 0 1.91374 0 1.22676C0 0.539773 0.539773 0 1.22676 0Z' fill='rgba(0,0,0,0.07)'/%3E%3C/svg%3E");
}
@media (prefers-color-scheme: dark) {
    .dark\:bg-dots-lighter {
        background-image: url("data:image/svg+xml,%3Csvg width='30' height='30' viewBox='0 0 30 30' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath d='M1.22676 0C1.91374 0 2.45351 0.539773 2.45351 1.22676C2.45351 1.91374 1.91374 2.45351 1.22676 2.45351C0.539773 2.45351 0 1.91374 0 1.22676C0 0.539773 0.539773 0 1.22676 0Z' fill='rgba(255,255,255,0.07)'/%3E%3C/svg%3E");
    }
}
</style>
