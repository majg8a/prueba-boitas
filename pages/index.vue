<template>
  <!---->
  <div>
    <header data-v-450d52fa="" class="top-header">
      <div data-v-450d52fa="" class="block sm:w-10/12 sm:mx-auto sm:py-1">
        <div data-v-450d52fa="" class="hidden sm:grid sm:grid-cols-2 sm:gap-5">
          <div data-v-450d52fa="" class="flex">
            <a
              data-v-450d52fa=""
              href="https://empresas.boitas.com/"
              class="mr-9 block self-center nuxt-link-active"
              ><img
                data-v-450d52fa=""
                src="logo-empresas.png"
                class="h-auto w-auto max-h-16 max-w-16"
            /></a>
            <div
              data-v-63538b22=""
              data-v-450d52fa=""
              id="top-search-container"
              class="relative w-9/12 py-2"
            >
              <form data-v-63538b22="" autocomplete="off">
                <input
                  data-v-63538b22=""
                  id="search-input"
                  type="text"
                  name="q"
                  placeholder="¿Qué estás buscando?"
                  class="header-search focus:outline-none"
                />
              </form>
              <div
                data-v-63538b22=""
                class="search-results"
                style="display: none"
              >
                <ul data-v-63538b22="">
                  <li data-v-63538b22="">
                    <h4 data-v-63538b22="" class="text-sm font-medium">
                      PRODUCTOS
                    </h4>
                    <ul data-v-63538b22="" class="search-results-items">
                      <!---->
                    </ul>
                  </li>
                </ul>
              </div>
            </div>
          </div>
          <div data-v-450d52fa="" class="flex justify-end">
            <button data-v-450d52fa="" class="mr-1 my-auto btn btn-white">
              Iniciar sesion
            </button>
            <a
              data-v-450d52fa=""
              href="https://empresas.boitas.com/register"
              class="mr-2 my-auto btn btn-orange"
              >Registrarme
            </a>
            <div data-v-360acaeb="" data-v-450d52fa="" class="self-center">
              <a
                data-v-360acaeb=""
                href="https://empresas.boitas.com/cart"
                class="z-50 pr-3 py-2 text-gray-700 flex relative"
                ><svg
                  data-v-360acaeb=""
                  xmlns="http://www.w3.org/2000/svg"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  class="h-7 w-7"
                  style="--darkreader-inline-stroke: currentColor"
                  data-darkreader-inline-stroke=""
                >
                  <path
                    data-v-360acaeb=""
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.184 1.707.707 1.707H17m0 0a2 2 0 100 4 2 2 0 000-4zm-8 2a2 2 0 11-4 0 2 2 0 014 0z"
                  ></path>
                </svg>
                <span
                  data-v-360acaeb=""
                  class="
                    inline-flex
                    badge-pos
                    items-center
                    justify-center
                    mr-2
                    text-xs
                    font-bold
                    leading-none
                    text-red-100
                    bg-red-500
                    rounded-full
                  "
                >
                  0
                </span></a
              >
            </div>
          </div>
        </div>
        <div
          data-v-450d52fa=""
          class="text-gray-100 pt-2 pb-1 flex justify-between sm:hidden"
        >
          <button
            data-v-450d52fa=""
            class="
              z-50
              mobile-menu-button
              mx-3
              pr-0
              py-0
              focus:outline-none
              text-gray-900
            "
          >
            <div data-v-450d52fa="" class="h-7 w-7">
              <svg
                data-v-450d52fa=""
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
                class="h-7 w-7 absolute"
                style="--darkreader-inline-stroke: currentColor"
                data-darkreader-inline-stroke=""
              >
                <path
                  data-v-450d52fa=""
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M4 6h16M4 12h16M4 18h16"
                ></path>
              </svg>
              <!---->
            </div>
          </button>
          <a
            data-v-450d52fa=""
            href="https://empresas.boitas.com/"
            class="
              z-50
              block
              text-white
              font-bold
              self-center
              w-2/4
              nuxt-link-active
            "
            ><img
              data-v-450d52fa=""
              src="logo-empresas.png"
              class="h-11 md:h-8"
          /></a>
          <button
            data-v-450d52fa=""
            outline="none"
            class="
              z-50
              block
              px-0
              py-2
              text-gray-700
              self-center
              mr-1
              focus:outline-none
            "
          >
            <svg
              data-v-450d52fa=""
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
              class="h-7 w-7"
              style="--darkreader-inline-stroke: currentColor"
              data-darkreader-inline-stroke=""
            >
              <path
                data-v-450d52fa=""
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"
              ></path>
            </svg>
          </button>
          <button
            data-v-450d52fa=""
            class="
              z-50
              block
              px-0
              py-2
              text-gray-700
              self-center
              mr-1
              focus:outline-none
            "
          >
            <svg
              data-v-450d52fa=""
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
              class="h-7 w-7"
              style="--darkreader-inline-stroke: currentColor"
              data-darkreader-inline-stroke=""
            >
              <path
                data-v-450d52fa=""
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M11 16l-4-4m0 0l4-4m-4 4h14m-5 4v1a3 3 0 01-3 3H6a3 3 0 01-3-3V7a3 3 0 013-3h7a3 3 0 013 3v1"
              ></path>
            </svg>
          </button>
          <a
            data-v-450d52fa=""
            href="https://empresas.boitas.com/register"
            class="z-50 block px-0 py-2 text-gray-700 self-center mr-1"
            ><svg
              data-v-450d52fa=""
              fill="none"
              stroke="currentColor"
              viewBox="0 0 24 24"
              xmlns="http://www.w3.org/2000/svg"
              class="w-7 h-7"
              style="--darkreader-inline-stroke: currentColor"
              data-darkreader-inline-stroke=""
            >
              <path
                data-v-450d52fa=""
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z"
              ></path></svg
          ></a>
          <div data-v-360acaeb="" data-v-450d52fa="">
            <a
              data-v-360acaeb=""
              href="https://empresas.boitas.com/cart"
              class="z-50 pr-3 py-2 text-gray-700 flex relative"
              ><svg
                data-v-360acaeb=""
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
                class="h-7 w-7"
                style="--darkreader-inline-stroke: currentColor"
                data-darkreader-inline-stroke=""
              >
                <path
                  data-v-360acaeb=""
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.184 1.707.707 1.707H17m0 0a2 2 0 100 4 2 2 0 000-4zm-8 2a2 2 0 11-4 0 2 2 0 014 0z"
                ></path>
              </svg>
              <span
                data-v-360acaeb=""
                class="
                  inline-flex
                  badge-pos
                  items-center
                  justify-center
                  mr-2
                  text-xs
                  font-bold
                  leading-none
                  text-red-100
                  bg-red-500
                  rounded-full
                "
              >
                0
              </span></a
            >
          </div>
        </div>
        <div
          data-v-450d52fa=""
          class="
            sm:block sm:transition-none sm:transform-none
            sidebar
            transform
            transition
            duration-200
            ease-in-out
            -translate-x-full
          "
        >
          <nav data-v-450d52fa="">
            <ul
              data-v-7b989da7=""
              data-v-450d52fa=""
              class="
                text-base
                sm:text-sm sm:flex
                pt-6
                sm:pt-2
                list-none
                top-menu
              "
            >
              <!-- <div data-v-7b989da7="" class="flex sm:hidden">
                <li data-v-7b989da7="" class="has-submenu flex text-gray-900">
                  <a data-v-7b989da7="" href="#" class="has-submenu flex p-3">
                    Categorías
                  </a>
                  <ul  id="drop" class="submenuhidden" v-if="categories">
                    <li  v-for="category in categories.categoryFeed" :key="category.id">
                      <a

                        href="https://empresas.boitas.com/categoria/cordones-broches"

                      >
                        {{ category.name }}
                      </a>
                    </li>
                  </ul>
                </li>
              </div> -->
              <div data-v-7b989da7="" class="hidden sm:flex">
                <li data-v-7b989da7="" class="has-submenu sm:text-gray-500">
                  <a
                    data-v-7b989da7=""
                    href="#"
                    class="has-submenu p-3 sm:p-2.5"
                  >
                    Categorías
                  </a>
                  <ul
                    data-v-7b989da7=""
                    id="dropD"
                    class="submenudesktop submenu"
                    v-if="categories"
                  >
                    <li
                      v-for="category in categories.categoryFeed"
                      :key="category.id"
                      data-v-7b989da7=""
                    >
                      <a data-v-7b989da7="">
                        {{ category.name }}
                      </a>
                    </li>
                  </ul>
                </li>
                <li data-v-7b989da7="" class="has-submenu sm:text-gray-500">
                  <a
                    data-v-7b989da7=""
                    href="https://empresas.boitas.com/regalos-e-incentivos"
                    class="p-3 sm:p-2.5"
                  >
                    Regalos e incentivos
                  </a>
                </li>
              </div>
            </ul>
          </nav>
        </div>
        <div
          data-v-450d52fa=""
          class="
            sm:hidden
            z-10
            w-screen
            bg-white
            h-14
            px-2
            absolute
            inset-x-0
            top-0
            transform
            translate-y-14
            md:relative md:translate-y-0
            transition
            duration-200
            ease-in-out
            -translate-y-full
          "
        >
          <div
            data-v-63538b22=""
            data-v-450d52fa=""
            id="top-search-container"
            class="relative w-full pt-2 pb-2 mx-auto"
          >
            <form data-v-63538b22="" autocomplete="off">
              <input
                data-v-63538b22=""
                id="search-input"
                type="text"
                name="q"
                placeholder="¿Qué estás buscando?"
                class="header-search focus:outline-none"
              />
            </form>
            <div
              data-v-63538b22=""
              class="search-results"
              style="display: none"
            >
              <ul data-v-63538b22="">
                <li data-v-63538b22="">
                  <h4 data-v-63538b22="" class="text-sm font-medium">
                    PRODUCTOS
                  </h4>
                  <ul data-v-63538b22="" class="search-results-items">
                    <!---->
                  </ul>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </header>
    <div class="md:flex w-11/12 mx-auto appNuxt">
      <div class="md:w-3/12 mr-7 border-r border-gray-200">
        <div class="mb-2">
          <h4 class="text-xl font-medium mb-2">Categorias</h4>
          <ul>
            <!---->
            <li>
              <span class="cursor-pointer hover:text-red-500 font-medium">
                ARTICULOS COMPUTADORA
              </span>
            </li>
          </ul>
        </div>
        <div class="mb-2">
          <h4 class="text-xl font-medium mb-2">Precios</h4>
          <!---->
          <ul class="mb-2">
            <li class="cursor-pointer hover:text-red-500">
              <span> Menor a $149 </span>
            </li>
          </ul>
          <div class="flex space-x-2 w-9/12">
            <div class="flex space-x-2">
              <input
                type="number"
                placeholder="Min"
                class="bg-gray-200 px-1.5 py-1 rounded w-6/12"
              />
              <input
                type="number"
                placeholder="Max"
                class="bg-gray-200 px-1.5 py-1 rounded w-6/12"
              />
            </div>
            <button
              class="
                bg-red-500
                px-1.5
                py-1
                rounded
                text-white
                w-5/12
                disabled:opacity-90
              "
            >
              Ir
            </button>
          </div>
        </div>
        <div>
          <div class="mb-2">
            <h4 class="text-xl font-medium mb-2">Tiendas</h4>
            <ul>
              <li>
                <label for="checkbox-SAIT" class="flex items-center space-x-2"
                  ><input id="checkbox-SAIT" type="checkbox" />
                  <span>SAIT</span> <span>(6)</span></label
                >
              </li>
            </ul>
          </div>
          <div class="mb-2">
            <h4 class="text-xl font-medium mb-2">Marcas</h4>
          </div>
        </div>
      </div>
      <div class="md:w-8/12">
        <nav class="w-full my-4 text-sm">
          <ol class="list-reset flex">
            <li>
              <a href="https://empresas.boitas.com/" class="nuxt-link-active">
                Inicio
              </a>
            </li>
            <li><span class="mx-2">/</span></li>
            <li class="text-gray-500">ARTICULOS COMPUTADORA</li>
          </ol>
        </nav>
        <h1 class="text-4xl mb-4 font-medium">ARTICULOS COMPUTADORA</h1>
        <div class="products-container" id="products-container">
          <div class="my-5">
            <ul
              class="
                w-full
                md:grid
                grid-cols-2
                md:grid-cols-4
                mt-5
                grid-rows-1
                md:gap-4
              "
              v-if="products"
            >
              <li
                class="mb-4 lg:mb-12"
                v-for="product in products.productFeed"
                :key="product.id"
              >
                <div data-v-616c2587="" class="product">
                  <a data-v-616c2587="" class=""
                    ><div data-v-616c2587="" class="product-image space-y-2">
                      <img
                        data-v-616c2587=""
                        :src="product.images[0].src"
                        alt="product"
                        class="mx-auto"
                      />
                      <div
                        data-v-616c2587=""
                        class="product-content text-left space-y-1 mx-4 pt-1"
                      >
                        <h2 data-v-616c2587="" class="h-8 break-words">
                          {{ product.name }}
                        </h2>
                        <div
                          data-v-616c2587=""
                          class="sending font-medium pt-1"
                        >
                          <h1 data-v-616c2587="">
                            <i
                              data-v-616c2587=""
                              class="fas fa-truck-loading mr-1"
                            ></i>
                            Envío gratis en México
                          </h1>
                        </div>
                        <div data-v-616c2587="" class="extra pb-2">
                          <p data-v-616c2587="" class="cost truncate">
                            ${{ product.price | decimalLimit }}
                          </p>
                        </div>
                      </div>
                    </div></a
                  >
                </div>
              </li>
            </ul>
          </div>
        </div>
        <div class="my-10 w-full" style="display: none">
          <img src="loader.gif" alt="loading" class="mx-auto" />
        </div>
      </div>
    </div>
    <footer>
      <div class="top-footer">
        <div class="container mx-auto py-6 px-1 md:w-10/12">
          <div
            class="
              grid
              md:grid-flow-col md:grid-cols-5
              gap-2
              text-center
              md:text-left
            "
          >
            <div class="footer-image mb-5">
              <img src="Recurso-3.png" class="w-full" />
            </div>
            <div>
              <div class="widget widget_nav_menu">
                <nav class="menu-footer-1-container" aria-label="Menu">
                  <ul id="menu-footer-1" class="menu">
                    <li
                      id="menu-item-24"
                      class="
                        menu-item
                        menu-item-type-custom
                        menu-item-object-custom
                        menu-item-24
                      "
                    >
                      <a href="#">Mi cuenta</a>
                    </li>
                    <li
                      id="menu-item-25"
                      class="
                        menu-item
                        menu-item-type-custom
                        menu-item-object-custom
                        menu-item-25
                      "
                    >
                      <a href="#">Mis pedidos</a>
                    </li>
                  </ul>
                </nav>
              </div>
            </div>
            <div>
              <div class="widget widget_nav_menu">
                <nav class="menu-footer-2-container" aria-label="Menu">
                  <ul id="menu-footer-2" class="menu">
                    <li
                      id="menu-item-20"
                      class="
                        menu-item
                        menu-item-type-custom
                        menu-item-object-custom
                        menu-item-20
                      "
                    >
                      <a href="#">Aviso de Privacidad</a>
                    </li>
                    <li
                      id="menu-item-21"
                      class="
                        menu-item
                        menu-item-type-custom
                        menu-item-object-custom
                        menu-item-21
                      "
                    >
                      <a href="#">Términos y Condiciones</a>
                    </li>
                    <li
                      id="menu-item-22"
                      class="
                        menu-item
                        menu-item-type-custom
                        menu-item-object-custom
                        menu-item-22
                      "
                    >
                      <a href="#">Cambios y Devoluciones</a>
                    </li>
                    <li
                      id="menu-item-23"
                      class="
                        menu-item
                        menu-item-type-custom
                        menu-item-object-custom
                        menu-item-23
                      "
                    >
                      <a href="#">Preguntas Frecuentes</a>
                    </li>
                  </ul>
                </nav>
              </div>
            </div>
            <div><div class="widget widget_nav_menu"></div></div>
          </div>
        </div>
      </div>
      <div class="container mx-auto px-1 md:w-10/12">
        <div class="w-full footer-text font-medium">
          <div class="metodos-de-pago">
            <img src="visa.htm" alt="visa" />
            <img src="mastercard.htm" alt="Mastercard" />
            <img
              src="amex.htm"
              data-src="https://s36180.pcdn.co/wp-content/plugins/woocommerce-gateway-stripe/assets/images/amex.svg"
              alt="AMEX"
            />
            <img src="PayPal.svg" alt="Paypal" />
            <img src="mercadopago.svg" alt="mercadopago" />
            <img src="logo-svg.svg" alt="Atrato" />
            <img src="spei_logo-1-1.png" alt="SPEI" />
          </div>
          <p class="mt-5 text-gray-800">
            Plataforma de Oportunidades SAPI de CV 2020. Todos los derechos
            reservados.
          </p>
        </div>
      </div>
      <div class="Cookie Cookie--bottom Cookie--base">
        <div class="Cookie__content">
          <div>
            Este sitio web utiliza cookies para garantizar que obtenga la mejor
            experiencia en nuestro sitio web.
          </div>
        </div>
        <div class="Cookie__buttons">
          <button class="Cookie__button">Entendido</button>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
import gql from 'graphql-tag'
export default {
  filters: {
    decimalLimit: (val) => `${Number.parseInt(val)}.${String(val)
        ?.split('.')[1]
        ?.split('')
        ?.filter((a, index) => index < 2)
        ?.join('')}`,
  },
  data: () => ({
    category: '',
  }),
  apollo: {
    categories: gql`
      query getProductCategories {
        categories(limit: 12, where: { parentId: null }) {
          categoryFeed {
            slug
            name
            id
            parentId
          }
        }
      }
    `,



    products: gql`
      query getProducts {
        products(limit: 24) {
          productFeed {
            name
            slug
            images {
              src
            }
            price
          }
        }
      }
    `,

    productsByCategory: gql`
      query getProductsFromCategory {
        productCategory(id: "belleza", idType: SLUG) {
          id
          name
          uri
          products(first: 12, where: { status: "publish", type: SIMPLE }) {
            nodes {
              id
              name
              slug
              description
              image {
                id
                uri
                title
                srcSet
                sourceUrl(size: SHOP_CATALOG)
              }
              ... on SimpleProduct {
                salePrice
                regularPrice
                price
              }
              ... on VariableProduct {
                salePrice
                price
                regularPrice
              }
            }
          }
        }
      }
    `,
  },
}
</script>

  <style >
.nuxt-progress {
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  height: 2px;
  width: 0;
  opacity: 1;
  transition: width 0.1s, opacity 0.4s;
  background-color: #000;
  z-index: 999999;
}
.nuxt-progress.nuxt-progress-notransition {
  transition: none;
}
.nuxt-progress-failed {
  background-color: red;
}

/*! tailwindcss v2.1.4 | MIT License | https://tailwindcss.com*/

/*! modern-normalize v1.1.0 | MIT License | https://github.com/sindresorhus/modern-normalize */

/*
Document
========
*/

/**
Use a better box model (opinionated).
*/

*,
::before,
::after {
  box-sizing: border-box;
}

/**
Use a more readable tab size (opinionated).
*/

html {
  -moz-tab-size: 4;
  -o-tab-size: 4;
  tab-size: 4;
}

/**
1. Correct the line height in all browsers.
2. Prevent adjustments of font size after orientation changes in iOS.
*/

html {
  line-height: 1.15; /* 1 */
  -webkit-text-size-adjust: 100%; /* 2 */
}

/*
Sections
========
*/

/**
Remove the margin in all browsers.
*/

body {
  margin: 0;
}

/**
Improve consistency of default fonts in all browsers. (https://github.com/sindresorhus/modern-normalize/issues/3)
*/

body {
  font-family: system-ui, -apple-system,
    /* Firefox supports this but not yet `system-ui` */ 'Segoe UI', Roboto,
    Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji';
}

/*
Grouping content
================
*/

/**
1. Add the correct height in Firefox.
2. Correct the inheritance of border color in Firefox. (https://bugzilla.mozilla.org/show_bug.cgi?id=190655)
*/

hr {
  height: 0; /* 1 */
  color: inherit; /* 2 */
}

/*
Text-level semantics
====================
*/

/**
Add the correct text decoration in Chrome, Edge, and Safari.
*/

abbr[title] {
  -webkit-text-decoration: underline dotted;
  text-decoration: underline dotted;
}

/**
Add the correct font weight in Edge and Safari.
*/

b,
strong {
  font-weight: bolder;
}

/**
1. Improve consistency of default fonts in all browsers. (https://github.com/sindresorhus/modern-normalize/issues/3)
2. Correct the odd 'em' font sizing in all browsers.
*/

code,
kbd,
samp,
pre {
  font-family: ui-monospace, SFMono-Regular, Consolas, 'Liberation Mono', Menlo,
    monospace; /* 1 */
  font-size: 1em; /* 2 */
}

/**
Add the correct font size in all browsers.
*/

small {
  font-size: 80%;
}

/**
Prevent 'sub' and 'sup' elements from affecting the line height in all browsers.
*/

sub,
sup {
  font-size: 75%;
  line-height: 0;
  position: relative;
  vertical-align: baseline;
}

sub {
  bottom: -0.25em;
}

sup {
  top: -0.5em;
}

/*
Tabular data
============
*/

/**
1. Remove text indentation from table contents in Chrome and Safari. (https://bugs.chromium.org/p/chromium/issues/detail?id=999088, https://bugs.webkit.org/show_bug.cgi?id=201297)
2. Correct table border color inheritance in all Chrome and Safari. (https://bugs.chromium.org/p/chromium/issues/detail?id=935729, https://bugs.webkit.org/show_bug.cgi?id=195016)
*/

table {
  text-indent: 0; /* 1 */
  border-color: inherit; /* 2 */
}

/*
Forms
=====
*/

/**
1. Change the font styles in all browsers.
2. Remove the margin in Firefox and Safari.
*/

button,
input,
optgroup,
select,
textarea {
  font-family: inherit; /* 1 */
  font-size: 100%; /* 1 */
  line-height: 1.15; /* 1 */
  margin: 0; /* 2 */
}

/**
Remove the inheritance of text transform in Edge and Firefox.
1. Remove the inheritance of text transform in Firefox.
*/

button,
select {
  /* 1 */
  text-transform: none;
}

/**
Correct the inability to style clickable types in iOS and Safari.
*/

button,
[type='button'],
[type='reset'],
[type='submit'] {
  -webkit-appearance: button;
}

/**
Remove the inner border and padding in Firefox.
*/

/**
Restore the focus styles unset by the previous rule.
*/

/**
Remove the additional ':invalid' styles in Firefox.
See: https://github.com/mozilla/gecko-dev/blob/2f9eacd9d3d995c937b4251a5557d95d494c9be1/layout/style/res/forms.css#L728-L737
*/

/**
Remove the padding so developers are not caught out when they zero out 'fieldset' elements in all browsers.
*/

legend {
  padding: 0;
}

/**
Add the correct vertical alignment in Chrome and Firefox.
*/

progress {
  vertical-align: baseline;
}

/**
Correct the cursor style of increment and decrement buttons in Safari.
*/

/**
1. Correct the odd appearance in Chrome and Safari.
2. Correct the outline style in Safari.
*/

[type='search'] {
  -webkit-appearance: textfield; /* 1 */
  outline-offset: -2px; /* 2 */
}

/**
Remove the inner padding in Chrome and Safari on macOS.
*/

/**
1. Correct the inability to style clickable types in iOS and Safari.
2. Change font properties to 'inherit' in Safari.
*/

/*
Interactive
===========
*/

/*
Add the correct display in Chrome and Safari.
*/

summary {
  display: list-item;
}

/**
 * Manually forked from SUIT CSS Base: https://github.com/suitcss/base
 * A thin layer on top of normalize.css that provides a starting point more
 * suitable for web applications.
 */

/**
 * Removes the default spacing and border for appropriate elements.
 */

blockquote,
dl,
dd,
h1,
h2,
h3,
h4,
h5,
h6,
hr,
figure,
p,
pre {
  margin: 0;
}

button {
  background-color: transparent;
  background-image: none;
}

/**
 * Work around a Firefox/IE bug where the transparent `button` background
 * results in a loss of the default `button` focus styles.
 */

button:focus {
  outline: 1px dotted;
  outline: 5px auto -webkit-focus-ring-color;
}

fieldset {
  margin: 0;
  padding: 0;
}

ol,
ul {
  list-style: none;
  margin: 0;
  padding: 0;
}

/**
 * Tailwind custom reset styles
 */

/**
 * 1. Use the user's configured `sans` font-family (with Tailwind's default
 *    sans-serif font stack as a fallback) as a sane default.
 * 2. Use Tailwind's default "normal" line-height so the user isn't forced
 *    to override it to ensure consistency even when using the default theme.
 */

html {
  font-family: ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, 'Noto Sans', sans-serif,
    'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji'; /* 1 */
  line-height: 1.5; /* 2 */
}

/**
 * Inherit font-family and line-height from `html` so users can set them as
 * a class directly on the `html` element.
 */

body {
  font-family: inherit;
  line-height: inherit;
}

/**
 * 1. Prevent padding and border from affecting element width.
 *
 *    We used to set this in the html element and inherit from
 *    the parent element for everything else. This caused issues
 *    in shadow-dom-enhanced elements like <details> where the content
 *    is wrapped by a div with box-sizing set to `content-box`.
 *
 *    https://github.com/mozdevs/cssremedy/issues/4
 *
 *
 * 2. Allow adding a border to an element by just adding a border-width.
 *
 *    By default, the way the browser specifies that an element should have no
 *    border is by setting it's border-style to `none` in the user-agent
 *    stylesheet.
 *
 *    In order to easily add borders to elements by just setting the `border-width`
 *    property, we change the default border-style for all elements to `solid`, and
 *    use border-width to hide them instead. This way our `border` utilities only
 *    need to set the `border-width` property instead of the entire `border`
 *    shorthand, making our border utilities much more straightforward to compose.
 *
 *    https://github.com/tailwindcss/tailwindcss/pull/116
 */

*,
::before,
::after {
  box-sizing: border-box; /* 1 */
  border-width: 0; /* 2 */
  border-style: solid; /* 2 */
  border-color: #e5e7eb; /* 2 */
}

/*
 * Ensure horizontal rules are visible by default
 */

hr {
  border-top-width: 1px;
}

/**
 * Undo the `border-style: none` reset that Normalize applies to images so that
 * our `border-{width}` utilities have the expected effect.
 *
 * The Normalize reset is unnecessary for us since we default the border-width
 * to 0 on all elements.
 *
 * https://github.com/tailwindcss/tailwindcss/issues/362
 */

img {
  border-style: solid;
}

textarea {
  resize: vertical;
}

input::-moz-placeholder,
textarea::-moz-placeholder {
  opacity: 1;
  color: #9ca3af;
}

input:-ms-input-placeholder,
textarea:-ms-input-placeholder {
  opacity: 1;
  color: #9ca3af;
}

input::placeholder,
textarea::placeholder {
  opacity: 1;
  color: #9ca3af;
}

button,
[role='button'] {
  cursor: pointer;
}

table {
  border-collapse: collapse;
}

h1,
h2,
h3,
h4,
h5,
h6 {
  font-size: inherit;
  font-weight: inherit;
}

/**
 * Reset links to optimize for opt-in styling instead of
 * opt-out.
 */

a {
  color: inherit;
  text-decoration: inherit;
}

/**
 * Reset form element properties that are easy to forget to
 * style explicitly so you don't inadvertently introduce
 * styles that deviate from your design system. These styles
 * supplement a partial reset that is already applied by
 * normalize.css.
 */

button,
input,
optgroup,
select,
textarea {
  padding: 0;
  line-height: inherit;
  color: inherit;
}

/**
 * Use the configured 'mono' font family for elements that
 * are expected to be rendered with a monospace font, falling
 * back to the system monospace stack if there is no configured
 * 'mono' font family.
 */

pre,
code,
kbd,
samp {
  font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas,
    'Liberation Mono', 'Courier New', monospace;
}

/**
 * Make replaced elements `display: block` by default as that's
 * the behavior you want almost all of the time. Inspired by
 * CSS Remedy, with `svg` added as well.
 *
 * https://github.com/mozdevs/cssremedy/issues/14
 */

img,
svg,
video,
canvas,
audio,
iframe,
embed,
object {
  display: block;
  vertical-align: middle;
}

/**
 * Constrain images and videos to the parent width and preserve
 * their intrinsic aspect ratio.
 *
 * https://github.com/mozdevs/cssremedy/issues/14
 */

img,
video {
  max-width: 100%;
  height: auto;
}

.container {
  width: 100%;
}

@media (min-width: 640px) {
  .container {
    max-width: 640px;
  }
}

@media (min-width: 768px) {
  .container {
    max-width: 768px;
  }
}

@media (min-width: 1024px) {
  .container {
    max-width: 1024px;
  }
}

@media (min-width: 1280px) {
  .container {
    max-width: 1280px;
  }
}

@media (min-width: 1536px) {
  .container {
    max-width: 1536px;
  }
}

.space-y-1 > :not([hidden]) ~ :not([hidden]) {
  --tw-space-y-reverse: 0;
  margin-top: calc(0.25rem * calc(1 - var(--tw-space-y-reverse)));
  margin-bottom: calc(0.25rem * var(--tw-space-y-reverse));
}

.space-y-2 > :not([hidden]) ~ :not([hidden]) {
  --tw-space-y-reverse: 0;
  margin-top: calc(0.5rem * calc(1 - var(--tw-space-y-reverse)));
  margin-bottom: calc(0.5rem * var(--tw-space-y-reverse));
}

.space-x-2 > :not([hidden]) ~ :not([hidden]) {
  --tw-space-x-reverse: 0;
  margin-right: calc(0.5rem * var(--tw-space-x-reverse));
  margin-left: calc(0.5rem * calc(1 - var(--tw-space-x-reverse)));
}

.space-x-4 > :not([hidden]) ~ :not([hidden]) {
  --tw-space-x-reverse: 0;
  margin-right: calc(1rem * var(--tw-space-x-reverse));
  margin-left: calc(1rem * calc(1 - var(--tw-space-x-reverse)));
}

.space-x-8 > :not([hidden]) ~ :not([hidden]) {
  --tw-space-x-reverse: 0;
  margin-right: calc(2rem * var(--tw-space-x-reverse));
  margin-left: calc(2rem * calc(1 - var(--tw-space-x-reverse)));
}

.bg-transparent {
  background-color: transparent;
}

.bg-black {
  --tw-bg-opacity: 1;
  background-color: rgba(0, 0, 0, var(--tw-bg-opacity));
}

.bg-white {
  --tw-bg-opacity: 1;
  background-color: rgba(255, 255, 255, var(--tw-bg-opacity));
}

.bg-gray-50 {
  --tw-bg-opacity: 1;
  background-color: rgba(249, 250, 251, var(--tw-bg-opacity));
}

.bg-gray-100 {
  --tw-bg-opacity: 1;
  background-color: rgba(243, 244, 246, var(--tw-bg-opacity));
}

.bg-gray-200 {
  --tw-bg-opacity: 1;
  background-color: rgba(229, 231, 235, var(--tw-bg-opacity));
}

.bg-gray-300 {
  --tw-bg-opacity: 1;
  background-color: rgba(209, 213, 219, var(--tw-bg-opacity));
}

.bg-gray-700 {
  --tw-bg-opacity: 1;
  background-color: rgba(55, 65, 81, var(--tw-bg-opacity));
}

.bg-gray-800 {
  --tw-bg-opacity: 1;
  background-color: rgba(31, 41, 55, var(--tw-bg-opacity));
}

.bg-gray-900 {
  --tw-bg-opacity: 1;
  background-color: rgba(17, 24, 39, var(--tw-bg-opacity));
}

.bg-red-100 {
  --tw-bg-opacity: 1;
  background-color: rgba(254, 226, 226, var(--tw-bg-opacity));
}

.bg-red-400 {
  --tw-bg-opacity: 1;
  background-color: rgba(248, 113, 113, var(--tw-bg-opacity));
}

.bg-red-500 {
  --tw-bg-opacity: 1;
  background-color: rgba(239, 68, 68, var(--tw-bg-opacity));
}

.bg-red-600 {
  --tw-bg-opacity: 1;
  background-color: rgba(220, 38, 38, var(--tw-bg-opacity));
}

.bg-yellow-100 {
  --tw-bg-opacity: 1;
  background-color: rgba(254, 243, 199, var(--tw-bg-opacity));
}

.bg-yellow-400 {
  --tw-bg-opacity: 1;
  background-color: rgba(251, 191, 36, var(--tw-bg-opacity));
}

.bg-yellow-500 {
  --tw-bg-opacity: 1;
  background-color: rgba(245, 158, 11, var(--tw-bg-opacity));
}

.bg-yellow-600 {
  --tw-bg-opacity: 1;
  background-color: rgba(217, 119, 6, var(--tw-bg-opacity));
}

.bg-green-100 {
  --tw-bg-opacity: 1;
  background-color: rgba(209, 250, 229, var(--tw-bg-opacity));
}

.bg-green-400 {
  --tw-bg-opacity: 1;
  background-color: rgba(52, 211, 153, var(--tw-bg-opacity));
}

.bg-green-500 {
  --tw-bg-opacity: 1;
  background-color: rgba(16, 185, 129, var(--tw-bg-opacity));
}

.bg-green-600 {
  --tw-bg-opacity: 1;
  background-color: rgba(5, 150, 105, var(--tw-bg-opacity));
}

.bg-blue-50 {
  --tw-bg-opacity: 1;
  background-color: rgba(239, 246, 255, var(--tw-bg-opacity));
}

.bg-blue-100 {
  --tw-bg-opacity: 1;
  background-color: rgba(219, 234, 254, var(--tw-bg-opacity));
}

.bg-blue-400 {
  --tw-bg-opacity: 1;
  background-color: rgba(96, 165, 250, var(--tw-bg-opacity));
}

.bg-blue-500 {
  --tw-bg-opacity: 1;
  background-color: rgba(59, 130, 246, var(--tw-bg-opacity));
}

.bg-blue-600 {
  --tw-bg-opacity: 1;
  background-color: rgba(37, 99, 235, var(--tw-bg-opacity));
}

.bg-indigo-100 {
  --tw-bg-opacity: 1;
  background-color: rgba(224, 231, 255, var(--tw-bg-opacity));
}

.bg-indigo-300 {
  --tw-bg-opacity: 1;
  background-color: rgba(165, 180, 252, var(--tw-bg-opacity));
}

.bg-indigo-400 {
  --tw-bg-opacity: 1;
  background-color: rgba(129, 140, 248, var(--tw-bg-opacity));
}

.bg-indigo-600 {
  --tw-bg-opacity: 1;
  background-color: rgba(79, 70, 229, var(--tw-bg-opacity));
}

.bg-indigo-700 {
  --tw-bg-opacity: 1;
  background-color: rgba(67, 56, 202, var(--tw-bg-opacity));
}

.bg-indigo-900 {
  --tw-bg-opacity: 1;
  background-color: rgba(49, 46, 129, var(--tw-bg-opacity));
}

.bg-purple-400 {
  --tw-bg-opacity: 1;
  background-color: rgba(167, 139, 250, var(--tw-bg-opacity));
}

.bg-purple-600 {
  --tw-bg-opacity: 1;
  background-color: rgba(124, 58, 237, var(--tw-bg-opacity));
}

.bg-pink-400 {
  --tw-bg-opacity: 1;
  background-color: rgba(244, 114, 182, var(--tw-bg-opacity));
}

.bg-pink-600 {
  --tw-bg-opacity: 1;
  background-color: rgba(219, 39, 119, var(--tw-bg-opacity));
}

.hover\:bg-white:hover {
  --tw-bg-opacity: 1;
  background-color: rgba(255, 255, 255, var(--tw-bg-opacity));
}

.hover\:bg-gray-50:hover {
  --tw-bg-opacity: 1;
  background-color: rgba(249, 250, 251, var(--tw-bg-opacity));
}

.hover\:bg-gray-100:hover {
  --tw-bg-opacity: 1;
  background-color: rgba(243, 244, 246, var(--tw-bg-opacity));
}

.hover\:bg-gray-600:hover {
  --tw-bg-opacity: 1;
  background-color: rgba(75, 85, 99, var(--tw-bg-opacity));
}

.hover\:bg-gray-800:hover {
  --tw-bg-opacity: 1;
  background-color: rgba(31, 41, 55, var(--tw-bg-opacity));
}

.hover\:bg-red-500:hover {
  --tw-bg-opacity: 1;
  background-color: rgba(239, 68, 68, var(--tw-bg-opacity));
}

.hover\:bg-yellow-500:hover {
  --tw-bg-opacity: 1;
  background-color: rgba(245, 158, 11, var(--tw-bg-opacity));
}

.hover\:bg-green-500:hover {
  --tw-bg-opacity: 1;
  background-color: rgba(16, 185, 129, var(--tw-bg-opacity));
}

.hover\:bg-blue-500:hover {
  --tw-bg-opacity: 1;
  background-color: rgba(59, 130, 246, var(--tw-bg-opacity));
}

.hover\:bg-indigo-50:hover {
  --tw-bg-opacity: 1;
  background-color: rgba(238, 242, 255, var(--tw-bg-opacity));
}

.hover\:bg-indigo-500:hover {
  --tw-bg-opacity: 1;
  background-color: rgba(99, 102, 241, var(--tw-bg-opacity));
}

.hover\:bg-indigo-700:hover {
  --tw-bg-opacity: 1;
  background-color: rgba(67, 56, 202, var(--tw-bg-opacity));
}

.hover\:bg-purple-500:hover {
  --tw-bg-opacity: 1;
  background-color: rgba(139, 92, 246, var(--tw-bg-opacity));
}

.hover\:bg-pink-500:hover {
  --tw-bg-opacity: 1;
  background-color: rgba(236, 72, 153, var(--tw-bg-opacity));
}

.border-transparent {
  border-color: transparent;
}

.border-white {
  --tw-border-opacity: 1;
  border-color: rgba(255, 255, 255, var(--tw-border-opacity));
}

.border-gray-50 {
  --tw-border-opacity: 1;
  border-color: rgba(249, 250, 251, var(--tw-border-opacity));
}

.border-gray-100 {
  --tw-border-opacity: 1;
  border-color: rgba(243, 244, 246, var(--tw-border-opacity));
}

.border-gray-200 {
  --tw-border-opacity: 1;
  border-color: rgba(229, 231, 235, var(--tw-border-opacity));
}

.border-gray-300 {
  --tw-border-opacity: 1;
  border-color: rgba(209, 213, 219, var(--tw-border-opacity));
}

.border-gray-400 {
  --tw-border-opacity: 1;
  border-color: rgba(156, 163, 175, var(--tw-border-opacity));
}

.border-gray-600 {
  --tw-border-opacity: 1;
  border-color: rgba(75, 85, 99, var(--tw-border-opacity));
}

.border-gray-800 {
  --tw-border-opacity: 1;
  border-color: rgba(31, 41, 55, var(--tw-border-opacity));
}

.border-gray-900 {
  --tw-border-opacity: 1;
  border-color: rgba(17, 24, 39, var(--tw-border-opacity));
}

.border-red-200 {
  --tw-border-opacity: 1;
  border-color: rgba(254, 202, 202, var(--tw-border-opacity));
}

.border-red-500 {
  --tw-border-opacity: 1;
  border-color: rgba(239, 68, 68, var(--tw-border-opacity));
}

.border-yellow-200 {
  --tw-border-opacity: 1;
  border-color: rgba(253, 230, 138, var(--tw-border-opacity));
}

.border-green-200 {
  --tw-border-opacity: 1;
  border-color: rgba(167, 243, 208, var(--tw-border-opacity));
}

.border-blue-200 {
  --tw-border-opacity: 1;
  border-color: rgba(191, 219, 254, var(--tw-border-opacity));
}

.focus\:border-red-500:focus {
  --tw-border-opacity: 1;
  border-color: rgba(239, 68, 68, var(--tw-border-opacity));
}

.focus\:border-red-700:focus {
  --tw-border-opacity: 1;
  border-color: rgba(185, 28, 28, var(--tw-border-opacity));
}

.focus\:border-yellow-700:focus {
  --tw-border-opacity: 1;
  border-color: rgba(180, 83, 9, var(--tw-border-opacity));
}

.focus\:border-green-700:focus {
  --tw-border-opacity: 1;
  border-color: rgba(4, 120, 87, var(--tw-border-opacity));
}

.focus\:border-blue-300:focus {
  --tw-border-opacity: 1;
  border-color: rgba(147, 197, 253, var(--tw-border-opacity));
}

.focus\:border-blue-600:focus {
  --tw-border-opacity: 1;
  border-color: rgba(37, 99, 235, var(--tw-border-opacity));
}

.focus\:border-blue-700:focus {
  --tw-border-opacity: 1;
  border-color: rgba(29, 78, 216, var(--tw-border-opacity));
}

.focus\:border-indigo-300:focus {
  --tw-border-opacity: 1;
  border-color: rgba(165, 180, 252, var(--tw-border-opacity));
}

.focus\:border-indigo-700:focus {
  --tw-border-opacity: 1;
  border-color: rgba(67, 56, 202, var(--tw-border-opacity));
}

.focus\:border-indigo-800:focus {
  --tw-border-opacity: 1;
  border-color: rgba(55, 48, 163, var(--tw-border-opacity));
}

.focus\:border-purple-700:focus {
  --tw-border-opacity: 1;
  border-color: rgba(109, 40, 217, var(--tw-border-opacity));
}

.focus\:border-pink-700:focus {
  --tw-border-opacity: 1;
  border-color: rgba(190, 24, 93, var(--tw-border-opacity));
}

.rounded-sm {
  border-radius: 0.125rem;
}

.rounded {
  border-radius: 0.25rem;
}

.rounded-md {
  border-radius: 0.375rem;
}

.rounded-lg {
  border-radius: 0.5rem;
}

.rounded-xl {
  border-radius: 0.75rem;
}

.rounded-full {
  border-radius: 9999px;
}

.rounded-r-md {
  border-top-right-radius: 0.375rem;
  border-bottom-right-radius: 0.375rem;
}

.rounded-l-md {
  border-top-left-radius: 0.375rem;
  border-bottom-left-radius: 0.375rem;
}

.rounded-tr-lg {
  border-top-right-radius: 0.5rem;
}

.rounded-br-lg {
  border-bottom-right-radius: 0.5rem;
}

.border-2 {
  border-width: 2px;
}

.border {
  border-width: 1px;
}

.border-r-0 {
  border-right-width: 0px;
}

.border-l-0 {
  border-left-width: 0px;
}

.border-b-2 {
  border-bottom-width: 2px;
}

.border-r {
  border-right-width: 1px;
}

.border-b {
  border-bottom-width: 1px;
}

.border-l {
  border-left-width: 1px;
}

.cursor-default {
  cursor: default;
}

.cursor-pointer {
  cursor: pointer;
}

.cursor-wait {
  cursor: wait;
}

.cursor-not-allowed {
  cursor: not-allowed;
}

.block {
  display: block;
}

.inline-block {
  display: inline-block;
}

.flex {
  display: flex;
}

.inline-flex {
  display: inline-flex;
}

.table {
  display: table;
}

.grid {
  display: grid;
}

.hidden {
  display: none;
}

.flex-col {
  flex-direction: column;
}

.flex-col-reverse {
  flex-direction: column-reverse;
}

.flex-wrap {
  flex-wrap: wrap;
}

.items-start {
  align-items: flex-start;
}

.items-end {
  align-items: flex-end;
}

.items-center {
  align-items: center;
}

.self-center {
  align-self: center;
}

.justify-end {
  justify-content: flex-end;
}

.justify-center {
  justify-content: center;
}

.justify-between {
  justify-content: space-between;
}

.flex-1 {
  flex: 1 1 0%;
}

.flex-shrink-0 {
  flex-shrink: 0;
}

.font-light {
  font-weight: 300;
}

.font-normal {
  font-weight: 400;
}

.font-medium {
  font-weight: 500;
}

.font-bold {
  font-weight: 700;
}

.h-0 {
  height: 0px;
}

.h-1 {
  height: 0.25rem;
}

.h-2 {
  height: 0.5rem;
}

.h-3 {
  height: 0.75rem;
}

.h-4 {
  height: 1rem;
}

.h-5 {
  height: 1.25rem;
}

.h-6 {
  height: 1.5rem;
}

.h-7 {
  height: 1.75rem;
}

.h-8 {
  height: 2rem;
}

.h-11 {
  height: 2.75rem;
}

.h-12 {
  height: 3rem;
}

.h-14 {
  height: 3.5rem;
}

.h-16 {
  height: 4rem;
}

.h-28 {
  height: 7rem;
}

.h-40 {
  height: 10rem;
}

.h-auto {
  height: auto;
}

.h-full {
  height: 100%;
}

.text-xs {
  font-size: 0.75rem;
  line-height: 1rem;
}

.text-sm {
  font-size: 0.875rem;
  line-height: 1.25rem;
}

.text-base {
  font-size: 1rem;
  line-height: 1.5rem;
}

.text-lg {
  font-size: 1.125rem;
  line-height: 1.75rem;
}

.text-xl {
  font-size: 1.25rem;
  line-height: 1.75rem;
}

.text-2xl {
  font-size: 1.5rem;
  line-height: 2rem;
}

.text-3xl {
  font-size: 1.875rem;
  line-height: 2.25rem;
}

.text-4xl {
  font-size: 2.25rem;
  line-height: 2.5rem;
}

.leading-4 {
  line-height: 1rem;
}

.leading-5 {
  line-height: 1.25rem;
}

.leading-6 {
  line-height: 1.5rem;
}

.leading-none {
  line-height: 1;
}

.list-none {
  list-style-type: none;
}

.my-2 {
  margin-top: 0.5rem;
  margin-bottom: 0.5rem;
}

.mx-2 {
  margin-left: 0.5rem;
  margin-right: 0.5rem;
}

.my-3 {
  margin-top: 0.75rem;
  margin-bottom: 0.75rem;
}

.mx-3 {
  margin-left: 0.75rem;
  margin-right: 0.75rem;
}

.my-4 {
  margin-top: 1rem;
  margin-bottom: 1rem;
}

.mx-4 {
  margin-left: 1rem;
  margin-right: 1rem;
}

.my-5 {
  margin-top: 1.25rem;
  margin-bottom: 1.25rem;
}

.my-10 {
  margin-top: 2.5rem;
  margin-bottom: 2.5rem;
}

.my-auto {
  margin-top: auto;
  margin-bottom: auto;
}

.mx-auto {
  margin-left: auto;
  margin-right: auto;
}

.-my-2 {
  margin-top: -0.5rem;
  margin-bottom: -0.5rem;
}

.-my-3 {
  margin-top: -0.75rem;
  margin-bottom: -0.75rem;
}

.ml-0 {
  margin-left: 0px;
}

.mt-1 {
  margin-top: 0.25rem;
}

.mr-1 {
  margin-right: 0.25rem;
}

.mt-2 {
  margin-top: 0.5rem;
}

.mr-2 {
  margin-right: 0.5rem;
}

.mb-2 {
  margin-bottom: 0.5rem;
}

.ml-2 {
  margin-left: 0.5rem;
}

.mt-3 {
  margin-top: 0.75rem;
}

.mr-3 {
  margin-right: 0.75rem;
}

.mb-3 {
  margin-bottom: 0.75rem;
}

.ml-3 {
  margin-left: 0.75rem;
}

.mt-4 {
  margin-top: 1rem;
}

.mr-4 {
  margin-right: 1rem;
}

.mb-4 {
  margin-bottom: 1rem;
}

.ml-4 {
  margin-left: 1rem;
}

.mt-5 {
  margin-top: 1.25rem;
}

.mb-5 {
  margin-bottom: 1.25rem;
}

.mr-7 {
  margin-right: 1.75rem;
}

.mb-8 {
  margin-bottom: 2rem;
}

.mr-9 {
  margin-right: 2.25rem;
}

.mb-12 {
  margin-bottom: 3rem;
}

.mr-auto {
  margin-right: auto;
}

.ml-0\.5 {
  margin-left: 0.125rem;
}

.-mt-1 {
  margin-top: -0.25rem;
}

.-mr-1 {
  margin-right: -0.25rem;
}

.-mr-14 {
  margin-right: -3.5rem;
}

.-mt-px {
  margin-top: -1px;
}

.-mb-px {
  margin-bottom: -1px;
}

.-ml-px {
  margin-left: -1px;
}

.max-h-7 {
  max-height: 1.75rem;
}

.max-h-16 {
  max-height: 4rem;
}

.max-w-sm {
  max-width: 24rem;
}

.max-w-md {
  max-width: 28rem;
}

.max-w-xl {
  max-width: 36rem;
}

.min-h-screen {
  min-height: 100vh;
}

.object-contain {
  -o-object-fit: contain;
  object-fit: contain;
}

.opacity-0 {
  opacity: 0;
}

.opacity-50 {
  opacity: 0.5;
}

.opacity-75 {
  opacity: 0.75;
}

.opacity-100 {
  opacity: 1;
}

.disabled\:opacity-50:disabled {
  opacity: 0.5;
}

.disabled\:opacity-90:disabled {
  opacity: 0.9;
}

.outline-none {
  outline: 2px solid transparent;
  outline-offset: 2px;
}

.focus\:outline-none:focus {
  outline: 2px solid transparent;
  outline-offset: 2px;
}

.overflow-hidden {
  overflow: hidden;
}

.overflow-y-auto {
  overflow-y: auto;
}

.p-1 {
  padding: 0.25rem;
}

.p-2 {
  padding: 0.5rem;
}

.p-3 {
  padding: 0.75rem;
}

.p-4 {
  padding: 1rem;
}

.p-5 {
  padding: 1.25rem;
}

.p-8 {
  padding: 2rem;
}

.py-0 {
  padding-top: 0px;
  padding-bottom: 0px;
}

.px-0 {
  padding-left: 0px;
  padding-right: 0px;
}

.py-1 {
  padding-top: 0.25rem;
  padding-bottom: 0.25rem;
}

.px-1 {
  padding-left: 0.25rem;
  padding-right: 0.25rem;
}

.py-2 {
  padding-top: 0.5rem;
  padding-bottom: 0.5rem;
}

.px-2 {
  padding-left: 0.5rem;
  padding-right: 0.5rem;
}

.py-3 {
  padding-top: 0.75rem;
  padding-bottom: 0.75rem;
}

.px-3 {
  padding-left: 0.75rem;
  padding-right: 0.75rem;
}

.py-4 {
  padding-top: 1rem;
  padding-bottom: 1rem;
}

.px-4 {
  padding-left: 1rem;
  padding-right: 1rem;
}

.py-5 {
  padding-top: 1.25rem;
  padding-bottom: 1.25rem;
}

.px-5 {
  padding-left: 1.25rem;
  padding-right: 1.25rem;
}

.py-6 {
  padding-top: 1.5rem;
  padding-bottom: 1.5rem;
}

.px-6 {
  padding-left: 1.5rem;
  padding-right: 1.5rem;
}

.py-7 {
  padding-top: 1.75rem;
  padding-bottom: 1.75rem;
}

.py-10 {
  padding-top: 2.5rem;
  padding-bottom: 2.5rem;
}

.py-1\.5 {
  padding-top: 0.375rem;
  padding-bottom: 0.375rem;
}

.px-1\.5 {
  padding-left: 0.375rem;
  padding-right: 0.375rem;
}

.px-2\.5 {
  padding-left: 0.625rem;
  padding-right: 0.625rem;
}

.pt-0 {
  padding-top: 0px;
}

.pr-0 {
  padding-right: 0px;
}

.pt-1 {
  padding-top: 0.25rem;
}

.pb-1 {
  padding-bottom: 0.25rem;
}

.pt-2 {
  padding-top: 0.5rem;
}

.pb-2 {
  padding-bottom: 0.5rem;
}

.pr-3 {
  padding-right: 0.75rem;
}

.pl-3 {
  padding-left: 0.75rem;
}

.pt-4 {
  padding-top: 1rem;
}

.pb-4 {
  padding-bottom: 1rem;
}

.pt-5 {
  padding-top: 1.25rem;
}

.pt-6 {
  padding-top: 1.5rem;
}

.pr-14 {
  padding-right: 3.5rem;
}

.pb-20 {
  padding-bottom: 5rem;
}

.pt-0\.5 {
  padding-top: 0.125rem;
}

.pointer-events-none {
  pointer-events: none;
}

.pointer-events-auto {
  pointer-events: auto;
}

.fixed {
  position: fixed;
}

.absolute {
  position: absolute;
}

.relative {
  position: relative;
}

.inset-0 {
  top: 0px;
  right: 0px;
  bottom: 0px;
  left: 0px;
}

.inset-x-0 {
  right: 0px;
  left: 0px;
}

.top-0 {
  top: 0px;
}

.right-0 {
  right: 0px;
}

.bottom-0 {
  bottom: 0px;
}

.left-0 {
  left: 0px;
}

* {
  --tw-shadow: 0 0 #0000;
}

.shadow-sm {
  --tw-shadow: 0 1px 2px 0 rgba(0, 0, 0, 0.05);
  box-shadow: var(--tw-ring-offset-shadow, 0 0 #0000),
    var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow);
}

.shadow-lg {
  --tw-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1),
    0 4px 6px -2px rgba(0, 0, 0, 0.05);
  box-shadow: var(--tw-ring-offset-shadow, 0 0 #0000),
    var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow);
}

.shadow-xl {
  --tw-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1),
    0 10px 10px -5px rgba(0, 0, 0, 0.04);
  box-shadow: var(--tw-ring-offset-shadow, 0 0 #0000),
    var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow);
}

* {
  --tw-ring-inset: var(--tw-empty, /*!*/ /*!*/);
  --tw-ring-offset-width: 0px;
  --tw-ring-offset-color: #fff;
  --tw-ring-color: rgba(59, 130, 246, 0.5);
  --tw-ring-offset-shadow: 0 0 #0000;
  --tw-ring-shadow: 0 0 #0000;
}

.focus\:ring-1:focus {
  --tw-ring-offset-shadow: var(--tw-ring-inset) 0 0 0
    var(--tw-ring-offset-width) var(--tw-ring-offset-color);
  --tw-ring-shadow: var(--tw-ring-inset) 0 0 0
    calc(1px + var(--tw-ring-offset-width)) var(--tw-ring-color);
  box-shadow: var(--tw-ring-offset-shadow), var(--tw-ring-shadow),
    var(--tw-shadow, 0 0 #0000);
}

.focus\:ring-2:focus {
  --tw-ring-offset-shadow: var(--tw-ring-inset) 0 0 0
    var(--tw-ring-offset-width) var(--tw-ring-offset-color);
  --tw-ring-shadow: var(--tw-ring-inset) 0 0 0
    calc(2px + var(--tw-ring-offset-width)) var(--tw-ring-color);
  box-shadow: var(--tw-ring-offset-shadow), var(--tw-ring-shadow),
    var(--tw-shadow, 0 0 #0000);
}

.focus\:ring-offset-2:focus {
  --tw-ring-offset-width: 2px;
}

.focus\:ring-indigo-500:focus {
  --tw-ring-opacity: 1;
  --tw-ring-color: rgba(99, 102, 241, var(--tw-ring-opacity));
}

.fill-current {
  fill: currentColor;
}

.table-fixed {
  table-layout: fixed;
}

.text-left {
  text-align: left;
}

.text-center {
  text-align: center;
}

.text-right {
  text-align: right;
}

.text-white {
  --tw-text-opacity: 1;
  color: rgba(255, 255, 255, var(--tw-text-opacity));
}

.text-gray-100 {
  --tw-text-opacity: 1;
  color: rgba(243, 244, 246, var(--tw-text-opacity));
}

.text-gray-200 {
  --tw-text-opacity: 1;
  color: rgba(229, 231, 235, var(--tw-text-opacity));
}

.text-gray-300 {
  --tw-text-opacity: 1;
  color: rgba(209, 213, 219, var(--tw-text-opacity));
}

.text-gray-400 {
  --tw-text-opacity: 1;
  color: rgba(156, 163, 175, var(--tw-text-opacity));
}

.text-gray-500 {
  --tw-text-opacity: 1;
  color: rgba(107, 114, 128, var(--tw-text-opacity));
}

.text-gray-600 {
  --tw-text-opacity: 1;
  color: rgba(75, 85, 99, var(--tw-text-opacity));
}

.text-gray-700 {
  --tw-text-opacity: 1;
  color: rgba(55, 65, 81, var(--tw-text-opacity));
}

.text-gray-800 {
  --tw-text-opacity: 1;
  color: rgba(31, 41, 55, var(--tw-text-opacity));
}

.text-gray-900 {
  --tw-text-opacity: 1;
  color: rgba(17, 24, 39, var(--tw-text-opacity));
}

.text-red-100 {
  --tw-text-opacity: 1;
  color: rgba(254, 226, 226, var(--tw-text-opacity));
}

.text-red-300 {
  --tw-text-opacity: 1;
  color: rgba(252, 165, 165, var(--tw-text-opacity));
}

.text-red-400 {
  --tw-text-opacity: 1;
  color: rgba(248, 113, 113, var(--tw-text-opacity));
}

.text-red-500 {
  --tw-text-opacity: 1;
  color: rgba(239, 68, 68, var(--tw-text-opacity));
}

.text-red-600 {
  --tw-text-opacity: 1;
  color: rgba(220, 38, 38, var(--tw-text-opacity));
}

.text-yellow-300 {
  --tw-text-opacity: 1;
  color: rgba(252, 211, 77, var(--tw-text-opacity));
}

.text-yellow-400 {
  --tw-text-opacity: 1;
  color: rgba(251, 191, 36, var(--tw-text-opacity));
}

.text-yellow-500 {
  --tw-text-opacity: 1;
  color: rgba(245, 158, 11, var(--tw-text-opacity));
}

.text-yellow-600 {
  --tw-text-opacity: 1;
  color: rgba(217, 119, 6, var(--tw-text-opacity));
}

.text-green-300 {
  --tw-text-opacity: 1;
  color: rgba(110, 231, 183, var(--tw-text-opacity));
}

.text-green-400 {
  --tw-text-opacity: 1;
  color: rgba(52, 211, 153, var(--tw-text-opacity));
}

.text-green-500 {
  --tw-text-opacity: 1;
  color: rgba(16, 185, 129, var(--tw-text-opacity));
}

.text-green-600 {
  --tw-text-opacity: 1;
  color: rgba(5, 150, 105, var(--tw-text-opacity));
}

.text-green-900 {
  --tw-text-opacity: 1;
  color: rgba(6, 78, 59, var(--tw-text-opacity));
}

.text-blue-300 {
  --tw-text-opacity: 1;
  color: rgba(147, 197, 253, var(--tw-text-opacity));
}

.text-blue-400 {
  --tw-text-opacity: 1;
  color: rgba(96, 165, 250, var(--tw-text-opacity));
}

.text-blue-500 {
  --tw-text-opacity: 1;
  color: rgba(59, 130, 246, var(--tw-text-opacity));
}

.text-blue-600 {
  --tw-text-opacity: 1;
  color: rgba(37, 99, 235, var(--tw-text-opacity));
}

.text-blue-900 {
  --tw-text-opacity: 1;
  color: rgba(30, 58, 138, var(--tw-text-opacity));
}

.text-indigo-100 {
  --tw-text-opacity: 1;
  color: rgba(224, 231, 255, var(--tw-text-opacity));
}

.text-indigo-200 {
  --tw-text-opacity: 1;
  color: rgba(199, 210, 254, var(--tw-text-opacity));
}

.text-indigo-600 {
  --tw-text-opacity: 1;
  color: rgba(79, 70, 229, var(--tw-text-opacity));
}

.text-indigo-700 {
  --tw-text-opacity: 1;
  color: rgba(67, 56, 202, var(--tw-text-opacity));
}

.hover\:text-white:hover {
  --tw-text-opacity: 1;
  color: rgba(255, 255, 255, var(--tw-text-opacity));
}

.hover\:text-gray-400:hover {
  --tw-text-opacity: 1;
  color: rgba(156, 163, 175, var(--tw-text-opacity));
}

.hover\:text-gray-500:hover {
  --tw-text-opacity: 1;
  color: rgba(107, 114, 128, var(--tw-text-opacity));
}

.hover\:text-gray-900:hover {
  --tw-text-opacity: 1;
  color: rgba(17, 24, 39, var(--tw-text-opacity));
}

.hover\:text-red-500:hover {
  --tw-text-opacity: 1;
  color: rgba(239, 68, 68, var(--tw-text-opacity));
}

.hover\:text-indigo-500:hover {
  --tw-text-opacity: 1;
  color: rgba(99, 102, 241, var(--tw-text-opacity));
}

.focus\:text-gray-500:focus {
  --tw-text-opacity: 1;
  color: rgba(107, 114, 128, var(--tw-text-opacity));
}

.truncate {
  overflow: hidden;
  text-overflow: ellipsis;
  white-space: nowrap;
}

.uppercase {
  text-transform: uppercase;
}

.underline {
  text-decoration: underline;
}

.focus\:underline:focus {
  text-decoration: underline;
}

.align-bottom {
  vertical-align: bottom;
}

.visible {
  visibility: visible;
}

.break-words {
  overflow-wrap: break-word;
}

.w-0 {
  width: 0px;
}

.w-3 {
  width: 0.75rem;
}

.w-4 {
  width: 1rem;
}

.w-5 {
  width: 1.25rem;
}

.w-6 {
  width: 1.5rem;
}

.w-7 {
  width: 1.75rem;
}

.w-12 {
  width: 3rem;
}

.w-16 {
  width: 4rem;
}

.w-28 {
  width: 7rem;
}

.w-40 {
  width: 10rem;
}

.w-auto {
  width: auto;
}

.w-1\/2 {
  width: 50%;
}

.w-2\/4 {
  width: 50%;
}

.w-5\/12 {
  width: 41.666667%;
}

.w-6\/12 {
  width: 50%;
}

.w-7\/12 {
  width: 58.333333%;
}

.w-8\/12 {
  width: 66.666667%;
}

.w-9\/12 {
  width: 75%;
}

.w-10\/12 {
  width: 83.333333%;
}

.w-11\/12 {
  width: 91.666667%;
}

.w-full {
  width: 100%;
}

.w-screen {
  width: 100vw;
}

.z-10 {
  z-index: 10;
}

.z-40 {
  z-index: 40;
}

.z-50 {
  z-index: 50;
}

.z-999 {
  z-index: 999;
}

.focus\:z-10:focus {
  z-index: 10;
}

.gap-1 {
  gap: 0.25rem;
}

.gap-2 {
  gap: 0.5rem;
}

.gap-3 {
  gap: 0.75rem;
}

.gap-4 {
  gap: 1rem;
}

.grid-flow-col {
  grid-auto-flow: column;
}

.grid-cols-2 {
  grid-template-columns: repeat(2, minmax(0, 1fr));
}

.auto-cols-max {
  grid-auto-columns: -webkit-max-content;
  grid-auto-columns: max-content;
}

.grid-rows-1 {
  grid-template-rows: repeat(1, minmax(0, 1fr));
}

.transform {
  --tw-translate-x: 0;
  --tw-translate-y: 0;
  --tw-rotate: 0;
  --tw-skew-x: 0;
  --tw-skew-y: 0;
  --tw-scale-x: 1;
  --tw-scale-y: 1;
  transform: translateX(var(--tw-translate-x)) translateY(var(--tw-translate-y))
    rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y))
    scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
}

.-translate-x-full {
  --tw-translate-x: -100%;
}

.translate-y-0 {
  --tw-translate-y: 0px;
}

.translate-y-1 {
  --tw-translate-y: 0.25rem;
}

.translate-y-2 {
  --tw-translate-y: 0.5rem;
}

.translate-y-4 {
  --tw-translate-y: 1rem;
}

.translate-y-14 {
  --tw-translate-y: 3.5rem;
}

.-translate-y-full {
  --tw-translate-y: -100%;
}

.transition-all {
  transition-property: all;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
  transition-duration: 150ms;
}

.transition {
  transition-property: background-color, border-color, color, fill, stroke,
    opacity, box-shadow, transform, filter, -webkit-backdrop-filter;
  transition-property: background-color, border-color, color, fill, stroke,
    opacity, box-shadow, transform, filter, backdrop-filter;
  transition-property: background-color, border-color, color, fill, stroke,
    opacity, box-shadow, transform, filter, backdrop-filter,
    -webkit-backdrop-filter;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
  transition-duration: 150ms;
}

.transition-opacity {
  transition-property: opacity;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
  transition-duration: 150ms;
}

.ease-in {
  transition-timing-function: cubic-bezier(0.4, 0, 1, 1);
}

.ease-out {
  transition-timing-function: cubic-bezier(0, 0, 0.2, 1);
}

.ease-in-out {
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
}

.duration-100 {
  transition-duration: 100ms;
}

.duration-150 {
  transition-duration: 150ms;
}

.duration-200 {
  transition-duration: 200ms;
}

.duration-300 {
  transition-duration: 300ms;
}

@-webkit-keyframes spin {
  to {
    transform: rotate(360deg);
  }
}

@keyframes spin {
  to {
    transform: rotate(360deg);
  }
}

@-webkit-keyframes ping {
  75%,
  100% {
    transform: scale(2);
    opacity: 0;
  }
}

@keyframes ping {
  75%,
  100% {
    transform: scale(2);
    opacity: 0;
  }
}

@-webkit-keyframes pulse {
  50% {
    opacity: 0.5;
  }
}

@keyframes pulse {
  50% {
    opacity: 0.5;
  }
}

@-webkit-keyframes bounce {
  0%,
  100% {
    transform: translateY(-25%);
    -webkit-animation-timing-function: cubic-bezier(0.8, 0, 1, 1);
    animation-timing-function: cubic-bezier(0.8, 0, 1, 1);
  }

  50% {
    transform: none;
    -webkit-animation-timing-function: cubic-bezier(0, 0, 0.2, 1);
    animation-timing-function: cubic-bezier(0, 0, 0.2, 1);
  }
}

@keyframes bounce {
  0%,
  100% {
    transform: translateY(-25%);
    -webkit-animation-timing-function: cubic-bezier(0.8, 0, 1, 1);
    animation-timing-function: cubic-bezier(0.8, 0, 1, 1);
  }

  50% {
    transform: none;
    -webkit-animation-timing-function: cubic-bezier(0, 0, 0.2, 1);
    animation-timing-function: cubic-bezier(0, 0, 0.2, 1);
  }
}

.animate-ping {
  -webkit-animation: ping 1s cubic-bezier(0, 0, 0.2, 1) infinite;
  animation: ping 1s cubic-bezier(0, 0, 0.2, 1) infinite;
}

.filter {
  --tw-blur: var(--tw-empty, /*!*/ /*!*/);
  --tw-brightness: var(--tw-empty, /*!*/ /*!*/);
  --tw-contrast: var(--tw-empty, /*!*/ /*!*/);
  --tw-grayscale: var(--tw-empty, /*!*/ /*!*/);
  --tw-hue-rotate: var(--tw-empty, /*!*/ /*!*/);
  --tw-invert: var(--tw-empty, /*!*/ /*!*/);
  --tw-saturate: var(--tw-empty, /*!*/ /*!*/);
  --tw-sepia: var(--tw-empty, /*!*/ /*!*/);
  --tw-drop-shadow: var(--tw-empty, /*!*/ /*!*/);
  filter: var(--tw-blur) var(--tw-brightness) var(--tw-contrast)
    var(--tw-grayscale) var(--tw-hue-rotate) var(--tw-invert) var(--tw-saturate)
    var(--tw-sepia) var(--tw-drop-shadow);
}

@media (min-width: 640px) {
  .sm\:block {
    display: block;
  }

  .sm\:inline-block {
    display: inline-block;
  }

  .sm\:flex {
    display: flex;
  }

  .sm\:grid {
    display: grid;
  }

  .sm\:hidden {
    display: none;
  }

  .sm\:flex-row-reverse {
    flex-direction: row-reverse;
  }

  .sm\:items-start {
    align-items: flex-start;
  }

  .sm\:items-end {
    align-items: flex-end;
  }

  .sm\:items-center {
    align-items: center;
  }

  .sm\:justify-end {
    justify-content: flex-end;
  }

  .sm\:h-10 {
    height: 2.5rem;
  }

  .sm\:h-screen {
    height: 100vh;
  }

  .sm\:text-sm {
    font-size: 0.875rem;
    line-height: 1.25rem;
  }

  .sm\:mx-0 {
    margin-left: 0px;
    margin-right: 0px;
  }

  .sm\:my-8 {
    margin-top: 2rem;
    margin-bottom: 2rem;
  }

  .sm\:mx-auto {
    margin-left: auto;
    margin-right: auto;
  }

  .sm\:mt-0 {
    margin-top: 0px;
  }

  .sm\:ml-3 {
    margin-left: 0.75rem;
  }

  .sm\:mt-4 {
    margin-top: 1rem;
  }

  .sm\:ml-4 {
    margin-left: 1rem;
  }

  .sm\:max-w-lg {
    max-width: 32rem;
  }

  .sm\:p-0 {
    padding: 0px;
  }

  .sm\:p-2 {
    padding: 0.5rem;
  }

  .sm\:p-6 {
    padding: 1.5rem;
  }

  .sm\:p-2\.5 {
    padding: 0.625rem;
  }

  .sm\:py-1 {
    padding-top: 0.25rem;
    padding-bottom: 0.25rem;
  }

  .sm\:pt-2 {
    padding-top: 0.5rem;
  }

  .sm\:text-left {
    text-align: left;
  }

  .sm\:text-gray-500 {
    --tw-text-opacity: 1;
    color: rgba(107, 114, 128, var(--tw-text-opacity));
  }

  .sm\:align-middle {
    vertical-align: middle;
  }

  .sm\:w-10 {
    width: 2.5rem;
  }

  .sm\:w-auto {
    width: auto;
  }

  .sm\:w-10\/12 {
    width: 83.333333%;
  }

  .sm\:w-full {
    width: 100%;
  }

  .sm\:gap-5 {
    gap: 1.25rem;
  }

  .sm\:grid-cols-2 {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }

  .sm\:transform-none {
    transform: none;
  }

  .sm\:scale-95 {
    --tw-scale-x: 0.95;
    --tw-scale-y: 0.95;
  }

  .sm\:scale-100 {
    --tw-scale-x: 1;
    --tw-scale-y: 1;
  }

  .sm\:translate-x-0 {
    --tw-translate-x: 0px;
  }

  .sm\:translate-x-1 {
    --tw-translate-x: 0.25rem;
  }

  .sm\:translate-x-2 {
    --tw-translate-x: 0.5rem;
  }

  .sm\:translate-y-0 {
    --tw-translate-y: 0px;
  }

  .sm\:transition-none {
    transition-property: none;
  }
}

@media (min-width: 768px) {
  .md\:space-x-5 > :not([hidden]) ~ :not([hidden]) {
    --tw-space-x-reverse: 0;
    margin-right: calc(1.25rem * var(--tw-space-x-reverse));
    margin-left: calc(1.25rem * calc(1 - var(--tw-space-x-reverse)));
  }

  .md\:space-x-12 > :not([hidden]) ~ :not([hidden]) {
    --tw-space-x-reverse: 0;
    margin-right: calc(3rem * var(--tw-space-x-reverse));
    margin-left: calc(3rem * calc(1 - var(--tw-space-x-reverse)));
  }

  .md\:border-r {
    border-right-width: 1px;
  }

  .md\:block {
    display: block;
  }

  .md\:flex {
    display: flex;
  }

  .md\:grid {
    display: grid;
  }

  .md\:hidden {
    display: none;
  }

  .md\:justify-center {
    justify-content: center;
  }

  .md\:h-8 {
    height: 2rem;
  }

  .md\:m-4 {
    margin: 1rem;
  }

  .md\:my-2 {
    margin-top: 0.5rem;
    margin-bottom: 0.5rem;
  }

  .md\:p-5 {
    padding: 1.25rem;
  }

  .md\:px-5 {
    padding-left: 1.25rem;
    padding-right: 1.25rem;
  }

  .md\:relative {
    position: relative;
  }

  .md\:text-left {
    text-align: left;
  }

  .md\:w-40 {
    width: 10rem;
  }

  .md\:w-2\/4 {
    width: 50%;
  }

  .md\:w-4\/5 {
    width: 80%;
  }

  .md\:w-3\/12 {
    width: 25%;
  }

  .md\:w-6\/12 {
    width: 50%;
  }

  .md\:w-7\/12 {
    width: 58.333333%;
  }

  .md\:w-8\/12 {
    width: 66.666667%;
  }

  .md\:w-9\/12 {
    width: 75%;
  }

  .md\:w-10\/12 {
    width: 83.333333%;
  }

  .md\:w-full {
    width: 100%;
  }

  .md\:gap-4 {
    gap: 1rem;
  }

  .md\:grid-flow-col {
    grid-auto-flow: column;
  }

  .md\:grid-cols-3 {
    grid-template-columns: repeat(3, minmax(0, 1fr));
  }

  .md\:grid-cols-4 {
    grid-template-columns: repeat(4, minmax(0, 1fr));
  }

  .md\:grid-cols-5 {
    grid-template-columns: repeat(5, minmax(0, 1fr));
  }

  .md\:translate-y-0 {
    --tw-translate-y: 0px;
  }
}

@media (min-width: 1024px) {
  .lg\:grid {
    display: grid;
  }

  .lg\:hidden {
    display: none;
  }

  .lg\:mb-12 {
    margin-bottom: 3rem;
  }

  .lg\:gap-4 {
    gap: 1rem;
  }

  .lg\:grid-cols-6 {
    grid-template-columns: repeat(6, minmax(0, 1fr));
  }
}

@media (min-width: 1280px) {
}

@media (min-width: 1536px) {
}

@font-face {
  font-family: 'DM Sans';

  font-style: normal;

  font-weight: 400;

  font-display: swap;

  src: url(/_nuxt/fonts/DMSans-Regular.067ebd7.ttf) format('truetype');
}

@font-face {
  font-family: 'DM Sans';

  font-style: normal;

  font-weight: 500;

  font-display: swap;

  src: url(/_nuxt/fonts/DMSans-Medium.f458346.ttf) format('truetype');
}

@font-face {
  font-family: 'DM Sans';

  font-style: normal;

  font-weight: 700;

  font-display: swap;

  src: url(/_nuxt/fonts/DMSans-Bold.da49214.ttf) format('truetype');
}

@font-face {
  font-family: 'ElegantIcons';

  src: url(/_nuxt/fonts/ElegantIcons.78ba4ad.eot);

  src: url(/_nuxt/fonts/ElegantIcons.78ba4ad.eot?#iefix)
      format('embedded-opentype'),
    url(/_nuxt/fonts/ElegantIcons.941bf29.woff) format('woff'),
    url(/_nuxt/fonts/ElegantIcons.4555dd9.ttf) format('truetype'),
    url(/_nuxt/img/ElegantIcons.a3709f8.svg#ElegantIcons) format('svg');

  font-weight: 400;

  font-style: normal;
}

.arrow_up:before {
  content: '!';
}

.arrow_down:before {
  content: '"';
}

.arrow_left:before {
  content: '#';
}

.arrow_right:before {
  content: '$';
}

.arrow_left-up:before {
  content: '%';
}

.arrow_right-up:before {
  content: '&';
}

.arrow_right-down:before {
  content: "'";
}

.arrow_left-down:before {
  content: '(';
}

.arrow-up-down:before {
  content: ')';
}

.arrow_up-down_alt:before {
  content: '*';
}

.arrow_left-right_alt:before {
  content: '+';
}

.arrow_left-right:before {
  content: ',';
}

.arrow_expand_alt2:before {
  content: '-';
}

.arrow_expand_alt:before {
  content: '.';
}

.arrow_condense:before {
  content: '/';
}

.arrow_expand:before {
  content: '0';
}

.arrow_move:before {
  content: '1';
}

.arrow_carrot-up:before {
  content: '2';
}

.arrow_carrot-down:before {
  content: '3';
}

.arrow_carrot-left:before {
  content: '4';
}

.arrow_carrot-right:before {
  content: '5';
}

.arrow_carrot-2up:before {
  content: '6';
}

.arrow_carrot-2down:before {
  content: '7';
}

.arrow_carrot-2left:before {
  content: '8';
}

.arrow_carrot-2right:before {
  content: '9';
}

.arrow_carrot-up_alt2:before {
  content: ':';
}

.arrow_carrot-down_alt2:before {
  content: ';';
}

.arrow_carrot-left_alt2:before {
  content: '<';
}

.arrow_carrot-right_alt2:before {
  content: '=';
}

.arrow_carrot-2up_alt2:before {
  content: '>';
}

.arrow_carrot-2down_alt2:before {
  content: '?';
}

.arrow_carrot-2left_alt2:before {
  content: '@';
}

.arrow_carrot-2right_alt2:before {
  content: 'A';
}

.arrow_triangle-up:before {
  content: 'B';
}

.arrow_triangle-down:before {
  content: 'C';
}

.arrow_triangle-left:before {
  content: 'D';
}

.arrow_triangle-right:before {
  content: 'E';
}

.arrow_triangle-up_alt2:before {
  content: 'F';
}

.arrow_triangle-down_alt2:before {
  content: 'G';
}

.arrow_triangle-left_alt2:before {
  content: 'H';
}

.arrow_triangle-right_alt2:before {
  content: 'I';
}

.arrow_back:before {
  content: 'J';
}

.icon_minus-06:before {
  content: 'K';
}

.icon_plus:before {
  content: 'L';
}

.icon_close:before {
  content: 'M';
}

.icon_check:before {
  content: 'N';
}

.icon_minus_alt2:before {
  content: 'O';
}

.icon_plus_alt2:before {
  content: 'P';
}

.icon_close_alt2:before {
  content: 'Q';
}

.icon_check_alt2:before {
  content: 'R';
}

.icon_zoom-out_alt:before {
  content: 'S';
}

.icon_zoom-in_alt:before {
  content: 'T';
}

.icon_search:before {
  content: 'U';
}

.icon_box-empty:before {
  content: 'V';
}

.icon_box-selected:before {
  content: 'W';
}

.icon_minus-box:before {
  content: 'X';
}

.icon_plus-box:before {
  content: 'Y';
}

.icon_box-checked:before {
  content: 'Z';
}

.icon_circle-empty:before {
  content: '[';
}

.icon_circle-slelected:before {
  content: '\\';
}

.icon_stop_alt2:before {
  content: ']';
}

.icon_stop:before {
  content: '^';
}

.icon_pause_alt2:before {
  content: '_';
}

.icon_pause:before {
  content: '`';
}

.icon_menu:before {
  content: 'a';
}

.icon_menu-square_alt2:before {
  content: 'b';
}

.icon_menu-circle_alt2:before {
  content: 'c';
}

.icon_ul:before {
  content: 'd';
}

.icon_ol:before {
  content: 'e';
}

.icon_adjust-horiz:before {
  content: 'f';
}

.icon_adjust-vert:before {
  content: 'g';
}

.icon_document_alt:before {
  content: 'h';
}

.icon_documents_alt:before {
  content: 'i';
}

.icon_pencil:before {
  content: 'j';
}

.icon_pencil-edit_alt:before {
  content: 'k';
}

.icon_pencil-edit:before {
  content: 'l';
}

.icon_folder-alt:before {
  content: 'm';
}

.icon_folder-open_alt:before {
  content: 'n';
}

.icon_folder-add_alt:before {
  content: 'o';
}

.icon_info_alt:before {
  content: 'p';
}

.icon_error-oct_alt:before {
  content: 'q';
}

.icon_error-circle_alt:before {
  content: 'r';
}

.icon_error-triangle_alt:before {
  content: 's';
}

.icon_question_alt2:before {
  content: 't';
}

.icon_question:before {
  content: 'u';
}

.icon_comment_alt:before {
  content: 'v';
}

.icon_chat_alt:before {
  content: 'w';
}

.icon_vol-mute_alt:before {
  content: 'x';
}

.icon_volume-low_alt:before {
  content: 'y';
}

.icon_volume-high_alt:before {
  content: 'z';
}

.icon_quotations:before {
  content: '{';
}

.icon_quotations_alt2:before {
  content: '|';
}

.icon_clock_alt:before {
  content: '}';
}

.icon_lock_alt:before {
  content: '~';
}

.icon_lock-open_alt:before {
  content: '';
}

.icon_key_alt:before {
  content: '';
}

.icon_cloud_alt:before {
  content: '';
}

.icon_cloud-upload_alt:before {
  content: '';
}

.icon_cloud-download_alt:before {
  content: '';
}

.icon_image:before {
  content: '';
}

.icon_images:before {
  content: '';
}

.icon_lightbulb_alt:before {
  content: '';
}

.icon_gift_alt:before {
  content: '';
}

.icon_house_alt:before {
  content: '';
}

.icon_genius:before {
  content: '';
}

.icon_mobile:before {
  content: '';
}

.icon_tablet:before {
  content: '';
}

.icon_laptop:before {
  content: '';
}

.icon_desktop:before {
  content: '';
}

.icon_camera_alt:before {
  content: '';
}

.icon_mail_alt:before {
  content: '';
}

.icon_cone_alt:before {
  content: '';
}

.icon_ribbon_alt:before {
  content: '';
}

.icon_bag_alt:before {
  content: '';
}

.icon_creditcard:before {
  content: '';
}

.icon_cart_alt:before {
  content: '';
}

.icon_paperclip:before {
  content: '';
}

.icon_tag_alt:before {
  content: '';
}

.icon_tags_alt:before {
  content: '';
}

.icon_trash_alt:before {
  content: '';
}

.icon_cursor_alt:before {
  content: '';
}

.icon_mic_alt:before {
  content: '';
}

.icon_compass_alt:before {
  content: '';
}

.icon_pin_alt:before {
  content: '';
}

.icon_pushpin_alt:before {
  content: '';
}

.icon_map_alt:before {
  content: '';
}

.icon_drawer_alt:before {
  content: '';
}

.icon_toolbox_alt:before {
  content: '';
}

.icon_book_alt:before {
  content: '';
}

.icon_calendar:before {
  content: '';
}

.icon_film:before {
  content: '';
}

.icon_table:before {
  content: '';
}

.icon_contacts_alt:before {
  content: '';
}

.icon_headphones:before {
  content: '';
}

.icon_lifesaver:before {
  content: '';
}

.icon_piechart:before {
  content: '';
}

.icon_refresh:before {
  content: '';
}

.icon_link_alt:before {
  content: '';
}

.icon_link:before {
  content: '';
}

.icon_loading:before {
  content: '';
}

.icon_blocked:before {
  content: '';
}

.icon_archive_alt:before {
  content: '';
}

.icon_heart_alt:before {
  content: '';
}

.icon_star_alt:before {
  content: '';
}

.icon_star-half_alt:before {
  content: '';
}

.icon_star:before {
  content: '';
}

.icon_star-half:before {
  content: '';
}

.icon_tools:before {
  content: '';
}

.icon_tool:before {
  content: '';
}

.icon_cog:before {
  content: '';
}

.icon_cogs:before {
  content: '';
}

.arrow_up_alt:before {
  content: '';
}

.arrow_down_alt:before {
  content: '';
}

.arrow_left_alt:before {
  content: '';
}

.arrow_right_alt:before {
  content: '';
}

.arrow_left-up_alt:before {
  content: '';
}

.arrow_right-up_alt:before {
  content: '';
}

.arrow_right-down_alt:before {
  content: '';
}

.arrow_left-down_alt:before {
  content: '';
}

.arrow_condense_alt:before {
  content: '';
}

.arrow_expand_alt3:before {
  content: '';
}

.arrow_carrot_up_alt:before {
  content: '';
}

.arrow_carrot-down_alt:before {
  content: '';
}

.arrow_carrot-left_alt:before {
  content: '';
}

.arrow_carrot-right_alt:before {
  content: '';
}

.arrow_carrot-2up_alt:before {
  content: '';
}

.arrow_carrot-2dwnn_alt:before {
  content: '';
}

.arrow_carrot-2left_alt:before {
  content: '';
}

.arrow_carrot-2right_alt:before {
  content: '';
}

.arrow_triangle-up_alt:before {
  content: '';
}

.arrow_triangle-down_alt:before {
  content: '';
}

.arrow_triangle-left_alt:before {
  content: '';
}

.arrow_triangle-right_alt:before {
  content: '';
}

.icon_minus_alt:before {
  content: '';
}

.icon_plus_alt:before {
  content: '';
}

.icon_close_alt:before {
  content: '';
}

.icon_check_alt:before {
  content: '';
}

.icon_zoom-out:before {
  content: '';
}

.icon_zoom-in:before {
  content: '';
}

.icon_stop_alt:before {
  content: '';
}

.icon_menu-square_alt:before {
  content: '';
}

.icon_menu-circle_alt:before {
  content: '';
}

.icon_document:before {
  content: '';
}

.icon_documents:before {
  content: '';
}

.icon_pencil_alt:before {
  content: '';
}

.icon_folder:before {
  content: '';
}

.icon_folder-open:before {
  content: '';
}

.icon_folder-add:before {
  content: '';
}

.icon_folder_upload:before {
  content: '';
}

.icon_folder_download:before {
  content: '';
}

.icon_info:before {
  content: '';
}

.icon_error-circle:before {
  content: '';
}

.icon_error-oct:before {
  content: '';
}

.icon_error-triangle:before {
  content: '';
}

.icon_question_alt:before {
  content: '';
}

.icon_comment:before {
  content: '';
}

.icon_chat:before {
  content: '';
}

.icon_vol-mute:before {
  content: '';
}

.icon_volume-low:before {
  content: '';
}

.icon_volume-high:before {
  content: '';
}

.icon_quotations_alt:before {
  content: '';
}

.icon_clock:before {
  content: '';
}

.icon_lock:before {
  content: '';
}

.icon_lock-open:before {
  content: '';
}

.icon_key:before {
  content: '';
}

.icon_cloud:before {
  content: '';
}

.icon_cloud-upload:before {
  content: '';
}

.icon_cloud-download:before {
  content: '';
}

.icon_lightbulb:before {
  content: '';
}

.icon_gift:before {
  content: '';
}

.icon_house:before {
  content: '';
}

.icon_camera:before {
  content: '';
}

.icon_mail:before {
  content: '';
}

.icon_cone:before {
  content: '';
}

.icon_ribbon:before {
  content: '';
}

.icon_bag:before {
  content: '';
}

.icon_cart:before {
  content: '';
}

.icon_tag:before {
  content: '';
}

.icon_tags:before {
  content: '';
}

.icon_trash:before {
  content: '';
}

.icon_cursor:before {
  content: '';
}

.icon_mic:before {
  content: '';
}

.icon_compass:before {
  content: '';
}

.icon_pin:before {
  content: '';
}

.icon_pushpin:before {
  content: '';
}

.icon_map:before {
  content: '';
}

.icon_drawer:before {
  content: '';
}

.icon_toolbox:before {
  content: '';
}

.icon_book:before {
  content: '';
}

.icon_contacts:before {
  content: '';
}

.icon_archive:before {
  content: '';
}

.icon_heart:before {
  content: '';
}

.icon_profile:before {
  content: '';
}

.icon_group:before {
  content: '';
}

.icon_grid-2x2:before {
  content: '';
}

.icon_grid-3x3:before {
  content: '';
}

.icon_music:before {
  content: '';
}

.icon_pause_alt:before {
  content: '';
}

.icon_phone:before {
  content: '';
}

.icon_upload:before {
  content: '';
}

.icon_download:before {
  content: '';
}

.social_facebook:before {
  content: '';
}

.social_twitter:before {
  content: '';
}

.social_pinterest:before {
  content: '';
}

.social_googleplus:before {
  content: '';
}

.social_tumblr:before {
  content: '';
}

.social_tumbleupon:before {
  content: '';
}

.social_wordpress:before {
  content: '';
}

.social_instagram:before {
  content: '';
}

.social_dribbble:before {
  content: '';
}

.social_vimeo:before {
  content: '';
}

.social_linkedin:before {
  content: '';
}

.social_rss:before {
  content: '';
}

.social_deviantart:before {
  content: '';
}

.social_share:before {
  content: '';
}

.social_myspace:before {
  content: '';
}

.social_skype:before {
  content: '';
}

.social_youtube:before {
  content: '';
}

.social_picassa:before {
  content: '';
}

.social_googledrive:before {
  content: '';
}

.social_flickr:before {
  content: '';
}

.social_blogger:before {
  content: '';
}

.social_spotify:before {
  content: '';
}

.social_delicious:before {
  content: '';
}

.social_facebook_circle:before {
  content: '';
}

.social_twitter_circle:before {
  content: '';
}

.social_pinterest_circle:before {
  content: '';
}

.social_googleplus_circle:before {
  content: '';
}

.social_tumblr_circle:before {
  content: '';
}

.social_stumbleupon_circle:before {
  content: '';
}

.social_wordpress_circle:before {
  content: '';
}

.social_instagram_circle:before {
  content: '';
}

.social_dribbble_circle:before {
  content: '';
}

.social_vimeo_circle:before {
  content: '';
}

.social_linkedin_circle:before {
  content: '';
}

.social_rss_circle:before {
  content: '';
}

.social_deviantart_circle:before {
  content: '';
}

.social_share_circle:before {
  content: '';
}

.social_myspace_circle:before {
  content: '';
}

.social_skype_circle:before {
  content: '';
}

.social_youtube_circle:before {
  content: '';
}

.social_picassa_circle:before {
  content: '';
}

.social_googledrive_alt2:before {
  content: '';
}

.social_flickr_circle:before {
  content: '';
}

.social_blogger_circle:before {
  content: '';
}

.social_spotify_circle:before {
  content: '';
}

.social_delicious_circle:before {
  content: '';
}

.social_facebook_square:before {
  content: '';
}

.social_twitter_square:before {
  content: '';
}

.social_pinterest_square:before {
  content: '';
}

.social_googleplus_square:before {
  content: '';
}

.social_tumblr_square:before {
  content: '';
}

.social_stumbleupon_square:before {
  content: '';
}

.social_wordpress_square:before {
  content: '';
}

.social_instagram_square:before {
  content: '';
}

.social_dribbble_square:before {
  content: '';
}

.social_vimeo_square:before {
  content: '';
}

.social_linkedin_square:before {
  content: '';
}

.social_rss_square:before {
  content: '';
}

.social_deviantart_square:before {
  content: '';
}

.social_share_square:before {
  content: '';
}

.social_myspace_square:before {
  content: '';
}

.social_skype_square:before {
  content: '';
}

.social_youtube_square:before {
  content: '';
}

.social_picassa_square:before {
  content: '';
}

.social_googledrive_square:before {
  content: '';
}

.social_flickr_square:before {
  content: '';
}

.social_blogger_square:before {
  content: '';
}

.social_spotify_square:before {
  content: '';
}

.social_delicious_square:before {
  content: '';
}

.icon_printer:before {
  content: '';
}

.icon_calulator:before {
  content: '';
}

.icon_building:before {
  content: '';
}

.icon_floppy:before {
  content: '';
}

.icon_drive:before {
  content: '';
}

.icon_search-2:before {
  content: '';
}

.icon_id:before {
  content: '';
}

.icon_id-2:before {
  content: '';
}

.icon_puzzle:before {
  content: '';
}

.icon_like:before {
  content: '';
}

.icon_dislike:before {
  content: '';
}

.icon_mug:before {
  content: '';
}

.icon_currency:before {
  content: '';
}

.icon_wallet:before {
  content: '';
}

.icon_pens:before {
  content: '';
}

.icon_easel:before {
  content: '';
}

.icon_flowchart:before {
  content: '';
}

.icon_datareport:before {
  content: '';
}

.icon_briefcase:before {
  content: '';
}

.icon_shield:before {
  content: '';
}

.icon_percent:before {
  content: '';
}

.icon_globe:before {
  content: '';
}

.icon_globe-2:before {
  content: '';
}

.icon_target:before {
  content: '';
}

.icon_hourglass:before {
  content: '';
}

.icon_balance:before {
  content: '';
}

.icon_rook:before {
  content: '';
}

.icon_printer-alt:before {
  content: '';
}

.icon_calculator_alt:before {
  content: '';
}

.icon_building_alt:before {
  content: '';
}

.icon_floppy_alt:before {
  content: '';
}

.icon_drive_alt:before {
  content: '';
}

.icon_search_alt:before {
  content: '';
}

.icon_id_alt:before {
  content: '';
}

.icon_id-2_alt:before {
  content: '';
}

.icon_puzzle_alt:before {
  content: '';
}

.icon_like_alt:before {
  content: '';
}

.icon_dislike_alt:before {
  content: '';
}

.icon_mug_alt:before {
  content: '';
}

.icon_currency_alt:before {
  content: '';
}

.icon_wallet_alt:before {
  content: '';
}

.icon_pens_alt:before {
  content: '';
}

.icon_easel_alt:before {
  content: '';
}

.icon_flowchart_alt:before {
  content: '';
}

.icon_datareport_alt:before {
  content: '';
}

.icon_briefcase_alt:before {
  content: '';
}

.icon_shield_alt:before {
  content: '';
}

.icon_percent_alt:before {
  content: '';
}

.icon_globe_alt:before {
  content: '';
}

.icon_clipboard:before {
  content: '';
}

.glyph {
  float: left;
  text-align: center;
  padding: 0.75em;
  margin: 0.4em 1.5em 0.75em 0;
  width: 6em;
  text-shadow: none;
}

.glyph_big {
  font-size: 128px;
  color: #59c5dc;
  float: left;
  margin-right: 20px;
}

.glyph div {
  padding-bottom: 10px;
}

.glyph input {
  font-family: consolas, monospace;
  font-size: 12px;
  width: 100%;
  text-align: center;
  border: 0;
  box-shadow: 0 0 0 1px #ccc;
  padding: 0.2em;
  -moz-border-radius: 5px;
  -webkit-border-radius: 5px;
}

.centered {
  margin-left: auto;
  margin-right: auto;
}

.glyph .fs1 {
  font-size: 2em;
}

body {
  font-family: 'DM Sans', sans-serif;
  margin-top: 125px;
}

.primary-color {
  color: #fd4a1f;
}

.extra {
  font-size: 14px;
}

.extra .gana {
  display: inline-block;
  background: 0 0;
  line-height: 1;
  border-radius: 40px;
  color: #5bbb67 !important;
  padding-bottom: 0 !important;
}

.extra .gana span {
  font-weight: 500;
}

.extra .lote {
  margin-top: 5px;
  padding: 0;
  color: #000;
  line-height: 16px;
}

.extra .amount {
  font-weight: 700;
  font-size: 20px;
  line-height: 24px;
}

.extra .venta {
  font-size: 14px;
  color: hsla(0, 0%, 40%, 0.4);
  margin-bottom: 0;
  padding-bottom: 0;
  line-height: 16px !important;
}

.extra .envio {
  color: #21bf5c;
  font-size: 14px;
  font-weight: 500;
}

div#toasts {
  justify-content: flex-start;
}

.swiper-pagination-bullet-active {
  background: #fd4a1f !important;
}

/*!
 * Font Awesome Free 5.15.3 by @fontawesome - https://fontawesome.com
 * License - https://fontawesome.com/license/free (Icons: CC BY 4.0, Fonts: SIL OFL 1.1, Code: MIT License)
 */

.fa,
.fab,
.fad,
.fal,
.far,
.fas {
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  display: inline-block;
  font-style: normal;
  font-variant: normal;
  text-rendering: auto;
  line-height: 1;
}

.fa-lg {
  font-size: 1.33333em;
  line-height: 0.75em;
  vertical-align: -0.0667em;
}

.fa-xs {
  font-size: 0.75em;
}

.fa-sm {
  font-size: 0.875em;
}

.fa-1x {
  font-size: 1em;
}

.fa-2x {
  font-size: 2em;
}

.fa-3x {
  font-size: 3em;
}

.fa-4x {
  font-size: 4em;
}

.fa-5x {
  font-size: 5em;
}

.fa-6x {
  font-size: 6em;
}

.fa-7x {
  font-size: 7em;
}

.fa-8x {
  font-size: 8em;
}

.fa-9x {
  font-size: 9em;
}

.fa-10x {
  font-size: 10em;
}

.fa-fw {
  text-align: center;
  width: 1.25em;
}

.fa-ul {
  list-style-type: none;
  margin-left: 2.5em;
  padding-left: 0;
}

.fa-ul > li {
  position: relative;
}

.fa-li {
  left: -2em;
  position: absolute;
  text-align: center;
  width: 2em;
  line-height: inherit;
}

.fa-border {
  border: 0.08em solid #eee;
  border-radius: 0.1em;
  padding: 0.2em 0.25em 0.15em;
}

.fa-pull-left {
  float: left;
}

.fa-pull-right {
  float: right;
}

.fa.fa-pull-left,
.fab.fa-pull-left,
.fal.fa-pull-left,
.far.fa-pull-left,
.fas.fa-pull-left {
  margin-right: 0.3em;
}

.fa.fa-pull-right,
.fab.fa-pull-right,
.fal.fa-pull-right,
.far.fa-pull-right,
.fas.fa-pull-right {
  margin-left: 0.3em;
}

.fa-spin {
  -webkit-animation: fa-spin 2s linear infinite;
  animation: fa-spin 2s linear infinite;
}

.fa-pulse {
  -webkit-animation: fa-spin 1s steps(8) infinite;
  animation: fa-spin 1s steps(8) infinite;
}

@-webkit-keyframes fa-spin {
  0% {
    transform: rotate(0deg);
  }

  to {
    transform: rotate(1turn);
  }
}

@keyframes fa-spin {
  0% {
    transform: rotate(0deg);
  }

  to {
    transform: rotate(1turn);
  }
}

.fa-rotate-90 {
  -ms-filter: 'progid:DXImageTransform.Microsoft.BasicImage(rotation=1)';
  transform: rotate(90deg);
}

.fa-rotate-180 {
  -ms-filter: 'progid:DXImageTransform.Microsoft.BasicImage(rotation=2)';
  transform: rotate(180deg);
}

.fa-rotate-270 {
  -ms-filter: 'progid:DXImageTransform.Microsoft.BasicImage(rotation=3)';
  transform: rotate(270deg);
}

.fa-flip-horizontal {
  -ms-filter: 'progid:DXImageTransform.Microsoft.BasicImage(rotation=0, mirror=1)';
  transform: scaleX(-1);
}

.fa-flip-vertical {
  transform: scaleY(-1);
}

.fa-flip-both,
.fa-flip-horizontal.fa-flip-vertical,
.fa-flip-vertical {
  -ms-filter: 'progid:DXImageTransform.Microsoft.BasicImage(rotation=2, mirror=1)';
}

.fa-flip-both,
.fa-flip-horizontal.fa-flip-vertical {
  transform: scale(-1);
}

:root .fa-flip-both,
:root .fa-flip-horizontal,
:root .fa-flip-vertical,
:root .fa-rotate-90,
:root .fa-rotate-180,
:root .fa-rotate-270 {
  filter: none;
}

.fa-stack {
  display: inline-block;
  height: 2em;
  line-height: 2em;
  position: relative;
  vertical-align: middle;
  width: 2.5em;
}

.fa-stack-1x,
.fa-stack-2x {
  left: 0;
  position: absolute;
  text-align: center;
  width: 100%;
}

.fa-stack-1x {
  line-height: inherit;
}

.fa-stack-2x {
  font-size: 2em;
}

.fa-inverse {
  color: #fff;
}

.fa-500px:before {
  content: '\f26e';
}

.fa-accessible-icon:before {
  content: '\f368';
}

.fa-accusoft:before {
  content: '\f369';
}

.fa-acquisitions-incorporated:before {
  content: '\f6af';
}

.fa-ad:before {
  content: '\f641';
}

.fa-address-book:before {
  content: '\f2b9';
}

.fa-address-card:before {
  content: '\f2bb';
}

.fa-adjust:before {
  content: '\f042';
}

.fa-adn:before {
  content: '\f170';
}

.fa-adversal:before {
  content: '\f36a';
}

.fa-affiliatetheme:before {
  content: '\f36b';
}

.fa-air-freshener:before {
  content: '\f5d0';
}

.fa-airbnb:before {
  content: '\f834';
}

.fa-algolia:before {
  content: '\f36c';
}

.fa-align-center:before {
  content: '\f037';
}

.fa-align-justify:before {
  content: '\f039';
}

.fa-align-left:before {
  content: '\f036';
}

.fa-align-right:before {
  content: '\f038';
}

.fa-alipay:before {
  content: '\f642';
}

.fa-allergies:before {
  content: '\f461';
}

.fa-amazon:before {
  content: '\f270';
}

.fa-amazon-pay:before {
  content: '\f42c';
}

.fa-ambulance:before {
  content: '\f0f9';
}

.fa-american-sign-language-interpreting:before {
  content: '\f2a3';
}

.fa-amilia:before {
  content: '\f36d';
}

.fa-anchor:before {
  content: '\f13d';
}

.fa-android:before {
  content: '\f17b';
}

.fa-angellist:before {
  content: '\f209';
}

.fa-angle-double-down:before {
  content: '\f103';
}

.fa-angle-double-left:before {
  content: '\f100';
}

.fa-angle-double-right:before {
  content: '\f101';
}

.fa-angle-double-up:before {
  content: '\f102';
}

.fa-angle-down:before {
  content: '\f107';
}

.fa-angle-left:before {
  content: '\f104';
}

.fa-angle-right:before {
  content: '\f105';
}

.fa-angle-up:before {
  content: '\f106';
}

.fa-angry:before {
  content: '\f556';
}

.fa-angrycreative:before {
  content: '\f36e';
}

.fa-angular:before {
  content: '\f420';
}

.fa-ankh:before {
  content: '\f644';
}

.fa-app-store:before {
  content: '\f36f';
}

.fa-app-store-ios:before {
  content: '\f370';
}

.fa-apper:before {
  content: '\f371';
}

.fa-apple:before {
  content: '\f179';
}

.fa-apple-alt:before {
  content: '\f5d1';
}

.fa-apple-pay:before {
  content: '\f415';
}

.fa-archive:before {
  content: '\f187';
}

.fa-archway:before {
  content: '\f557';
}

.fa-arrow-alt-circle-down:before {
  content: '\f358';
}

.fa-arrow-alt-circle-left:before {
  content: '\f359';
}

.fa-arrow-alt-circle-right:before {
  content: '\f35a';
}

.fa-arrow-alt-circle-up:before {
  content: '\f35b';
}

.fa-arrow-circle-down:before {
  content: '\f0ab';
}

.fa-arrow-circle-left:before {
  content: '\f0a8';
}

.fa-arrow-circle-right:before {
  content: '\f0a9';
}

.fa-arrow-circle-up:before {
  content: '\f0aa';
}

.fa-arrow-down:before {
  content: '\f063';
}

.fa-arrow-left:before {
  content: '\f060';
}

.fa-arrow-right:before {
  content: '\f061';
}

.fa-arrow-up:before {
  content: '\f062';
}

.fa-arrows-alt:before {
  content: '\f0b2';
}

.fa-arrows-alt-h:before {
  content: '\f337';
}

.fa-arrows-alt-v:before {
  content: '\f338';
}

.fa-artstation:before {
  content: '\f77a';
}

.fa-assistive-listening-systems:before {
  content: '\f2a2';
}

.fa-asterisk:before {
  content: '\f069';
}

.fa-asymmetrik:before {
  content: '\f372';
}

.fa-at:before {
  content: '\f1fa';
}

.fa-atlas:before {
  content: '\f558';
}

.fa-atlassian:before {
  content: '\f77b';
}

.fa-atom:before {
  content: '\f5d2';
}

.fa-audible:before {
  content: '\f373';
}

.fa-audio-description:before {
  content: '\f29e';
}

.fa-autoprefixer:before {
  content: '\f41c';
}

.fa-avianex:before {
  content: '\f374';
}

.fa-aviato:before {
  content: '\f421';
}

.fa-award:before {
  content: '\f559';
}

.fa-aws:before {
  content: '\f375';
}

.fa-baby:before {
  content: '\f77c';
}

.fa-baby-carriage:before {
  content: '\f77d';
}

.fa-backspace:before {
  content: '\f55a';
}

.fa-backward:before {
  content: '\f04a';
}

.fa-bacon:before {
  content: '\f7e5';
}

.fa-bacteria:before {
  content: '\e059';
}

.fa-bacterium:before {
  content: '\e05a';
}

.fa-bahai:before {
  content: '\f666';
}

.fa-balance-scale:before {
  content: '\f24e';
}

.fa-balance-scale-left:before {
  content: '\f515';
}

.fa-balance-scale-right:before {
  content: '\f516';
}

.fa-ban:before {
  content: '\f05e';
}

.fa-band-aid:before {
  content: '\f462';
}

.fa-bandcamp:before {
  content: '\f2d5';
}

.fa-barcode:before {
  content: '\f02a';
}

.fa-bars:before {
  content: '\f0c9';
}

.fa-baseball-ball:before {
  content: '\f433';
}

.fa-basketball-ball:before {
  content: '\f434';
}

.fa-bath:before {
  content: '\f2cd';
}

.fa-battery-empty:before {
  content: '\f244';
}

.fa-battery-full:before {
  content: '\f240';
}

.fa-battery-half:before {
  content: '\f242';
}

.fa-battery-quarter:before {
  content: '\f243';
}

.fa-battery-three-quarters:before {
  content: '\f241';
}

.fa-battle-net:before {
  content: '\f835';
}

.fa-bed:before {
  content: '\f236';
}

.fa-beer:before {
  content: '\f0fc';
}

.fa-behance:before {
  content: '\f1b4';
}

.fa-behance-square:before {
  content: '\f1b5';
}

.fa-bell:before {
  content: '\f0f3';
}

.fa-bell-slash:before {
  content: '\f1f6';
}

.fa-bezier-curve:before {
  content: '\f55b';
}

.fa-bible:before {
  content: '\f647';
}

.fa-bicycle:before {
  content: '\f206';
}

.fa-biking:before {
  content: '\f84a';
}

.fa-bimobject:before {
  content: '\f378';
}

.fa-binoculars:before {
  content: '\f1e5';
}

.fa-biohazard:before {
  content: '\f780';
}

.fa-birthday-cake:before {
  content: '\f1fd';
}

.fa-bitbucket:before {
  content: '\f171';
}

.fa-bitcoin:before {
  content: '\f379';
}

.fa-bity:before {
  content: '\f37a';
}

.fa-black-tie:before {
  content: '\f27e';
}

.fa-blackberry:before {
  content: '\f37b';
}

.fa-blender:before {
  content: '\f517';
}

.fa-blender-phone:before {
  content: '\f6b6';
}

.fa-blind:before {
  content: '\f29d';
}

.fa-blog:before {
  content: '\f781';
}

.fa-blogger:before {
  content: '\f37c';
}

.fa-blogger-b:before {
  content: '\f37d';
}

.fa-bluetooth:before {
  content: '\f293';
}

.fa-bluetooth-b:before {
  content: '\f294';
}

.fa-bold:before {
  content: '\f032';
}

.fa-bolt:before {
  content: '\f0e7';
}

.fa-bomb:before {
  content: '\f1e2';
}

.fa-bone:before {
  content: '\f5d7';
}

.fa-bong:before {
  content: '\f55c';
}

.fa-book:before {
  content: '\f02d';
}

.fa-book-dead:before {
  content: '\f6b7';
}

.fa-book-medical:before {
  content: '\f7e6';
}

.fa-book-open:before {
  content: '\f518';
}

.fa-book-reader:before {
  content: '\f5da';
}

.fa-bookmark:before {
  content: '\f02e';
}

.fa-bootstrap:before {
  content: '\f836';
}

.fa-border-all:before {
  content: '\f84c';
}

.fa-border-none:before {
  content: '\f850';
}

.fa-border-style:before {
  content: '\f853';
}

.fa-bowling-ball:before {
  content: '\f436';
}

.fa-box:before {
  content: '\f466';
}

.fa-box-open:before {
  content: '\f49e';
}

.fa-box-tissue:before {
  content: '\e05b';
}

.fa-boxes:before {
  content: '\f468';
}

.fa-braille:before {
  content: '\f2a1';
}

.fa-brain:before {
  content: '\f5dc';
}

.fa-bread-slice:before {
  content: '\f7ec';
}

.fa-briefcase:before {
  content: '\f0b1';
}

.fa-briefcase-medical:before {
  content: '\f469';
}

.fa-broadcast-tower:before {
  content: '\f519';
}

.fa-broom:before {
  content: '\f51a';
}

.fa-brush:before {
  content: '\f55d';
}

.fa-btc:before {
  content: '\f15a';
}

.fa-buffer:before {
  content: '\f837';
}

.fa-bug:before {
  content: '\f188';
}

.fa-building:before {
  content: '\f1ad';
}

.fa-bullhorn:before {
  content: '\f0a1';
}

.fa-bullseye:before {
  content: '\f140';
}

.fa-burn:before {
  content: '\f46a';
}

.fa-buromobelexperte:before {
  content: '\f37f';
}

.fa-bus:before {
  content: '\f207';
}

.fa-bus-alt:before {
  content: '\f55e';
}

.fa-business-time:before {
  content: '\f64a';
}

.fa-buy-n-large:before {
  content: '\f8a6';
}

.fa-buysellads:before {
  content: '\f20d';
}

.fa-calculator:before {
  content: '\f1ec';
}

.fa-calendar:before {
  content: '\f133';
}

.fa-calendar-alt:before {
  content: '\f073';
}

.fa-calendar-check:before {
  content: '\f274';
}

.fa-calendar-day:before {
  content: '\f783';
}

.fa-calendar-minus:before {
  content: '\f272';
}

.fa-calendar-plus:before {
  content: '\f271';
}

.fa-calendar-times:before {
  content: '\f273';
}

.fa-calendar-week:before {
  content: '\f784';
}

.fa-camera:before {
  content: '\f030';
}

.fa-camera-retro:before {
  content: '\f083';
}

.fa-campground:before {
  content: '\f6bb';
}

.fa-canadian-maple-leaf:before {
  content: '\f785';
}

.fa-candy-cane:before {
  content: '\f786';
}

.fa-cannabis:before {
  content: '\f55f';
}

.fa-capsules:before {
  content: '\f46b';
}

.fa-car:before {
  content: '\f1b9';
}

.fa-car-alt:before {
  content: '\f5de';
}

.fa-car-battery:before {
  content: '\f5df';
}

.fa-car-crash:before {
  content: '\f5e1';
}

.fa-car-side:before {
  content: '\f5e4';
}

.fa-caravan:before {
  content: '\f8ff';
}

.fa-caret-down:before {
  content: '\f0d7';
}

.fa-caret-left:before {
  content: '\f0d9';
}

.fa-caret-right:before {
  content: '\f0da';
}

.fa-caret-square-down:before {
  content: '\f150';
}

.fa-caret-square-left:before {
  content: '\f191';
}

.fa-caret-square-right:before {
  content: '\f152';
}

.fa-caret-square-up:before {
  content: '\f151';
}

.fa-caret-up:before {
  content: '\f0d8';
}

.fa-carrot:before {
  content: '\f787';
}

.fa-cart-arrow-down:before {
  content: '\f218';
}

.fa-cart-plus:before {
  content: '\f217';
}

.fa-cash-register:before {
  content: '\f788';
}

.fa-cat:before {
  content: '\f6be';
}

.fa-cc-amazon-pay:before {
  content: '\f42d';
}

.fa-cc-amex:before {
  content: '\f1f3';
}

.fa-cc-apple-pay:before {
  content: '\f416';
}

.fa-cc-diners-club:before {
  content: '\f24c';
}

.fa-cc-discover:before {
  content: '\f1f2';
}

.fa-cc-jcb:before {
  content: '\f24b';
}

.fa-cc-mastercard:before {
  content: '\f1f1';
}

.fa-cc-paypal:before {
  content: '\f1f4';
}

.fa-cc-stripe:before {
  content: '\f1f5';
}

.fa-cc-visa:before {
  content: '\f1f0';
}

.fa-centercode:before {
  content: '\f380';
}

.fa-centos:before {
  content: '\f789';
}

.fa-certificate:before {
  content: '\f0a3';
}

.fa-chair:before {
  content: '\f6c0';
}

.fa-chalkboard:before {
  content: '\f51b';
}

.fa-chalkboard-teacher:before {
  content: '\f51c';
}

.fa-charging-station:before {
  content: '\f5e7';
}

.fa-chart-area:before {
  content: '\f1fe';
}

.fa-chart-bar:before {
  content: '\f080';
}

.fa-chart-line:before {
  content: '\f201';
}

.fa-chart-pie:before {
  content: '\f200';
}

.fa-check:before {
  content: '\f00c';
}

.fa-check-circle:before {
  content: '\f058';
}

.fa-check-double:before {
  content: '\f560';
}

.fa-check-square:before {
  content: '\f14a';
}

.fa-cheese:before {
  content: '\f7ef';
}

.fa-chess:before {
  content: '\f439';
}

.fa-chess-bishop:before {
  content: '\f43a';
}

.fa-chess-board:before {
  content: '\f43c';
}

.fa-chess-king:before {
  content: '\f43f';
}

.fa-chess-knight:before {
  content: '\f441';
}

.fa-chess-pawn:before {
  content: '\f443';
}

.fa-chess-queen:before {
  content: '\f445';
}

.fa-chess-rook:before {
  content: '\f447';
}

.fa-chevron-circle-down:before {
  content: '\f13a';
}

.fa-chevron-circle-left:before {
  content: '\f137';
}

.fa-chevron-circle-right:before {
  content: '\f138';
}

.fa-chevron-circle-up:before {
  content: '\f139';
}

.fa-chevron-down:before {
  content: '\f078';
}

.fa-chevron-left:before {
  content: '\f053';
}

.fa-chevron-right:before {
  content: '\f054';
}

.fa-chevron-up:before {
  content: '\f077';
}

.fa-child:before {
  content: '\f1ae';
}

.fa-chrome:before {
  content: '\f268';
}

.fa-chromecast:before {
  content: '\f838';
}

.fa-church:before {
  content: '\f51d';
}

.fa-circle:before {
  content: '\f111';
}

.fa-circle-notch:before {
  content: '\f1ce';
}

.fa-city:before {
  content: '\f64f';
}

.fa-clinic-medical:before {
  content: '\f7f2';
}

.fa-clipboard:before {
  content: '\f328';
}

.fa-clipboard-check:before {
  content: '\f46c';
}

.fa-clipboard-list:before {
  content: '\f46d';
}

.fa-clock:before {
  content: '\f017';
}

.fa-clone:before {
  content: '\f24d';
}

.fa-closed-captioning:before {
  content: '\f20a';
}

.fa-cloud:before {
  content: '\f0c2';
}

.fa-cloud-download-alt:before {
  content: '\f381';
}

.fa-cloud-meatball:before {
  content: '\f73b';
}

.fa-cloud-moon:before {
  content: '\f6c3';
}

.fa-cloud-moon-rain:before {
  content: '\f73c';
}

.fa-cloud-rain:before {
  content: '\f73d';
}

.fa-cloud-showers-heavy:before {
  content: '\f740';
}

.fa-cloud-sun:before {
  content: '\f6c4';
}

.fa-cloud-sun-rain:before {
  content: '\f743';
}

.fa-cloud-upload-alt:before {
  content: '\f382';
}

.fa-cloudflare:before {
  content: '\e07d';
}

.fa-cloudscale:before {
  content: '\f383';
}

.fa-cloudsmith:before {
  content: '\f384';
}

.fa-cloudversify:before {
  content: '\f385';
}

.fa-cocktail:before {
  content: '\f561';
}

.fa-code:before {
  content: '\f121';
}

.fa-code-branch:before {
  content: '\f126';
}

.fa-codepen:before {
  content: '\f1cb';
}

.fa-codiepie:before {
  content: '\f284';
}

.fa-coffee:before {
  content: '\f0f4';
}

.fa-cog:before {
  content: '\f013';
}

.fa-cogs:before {
  content: '\f085';
}

.fa-coins:before {
  content: '\f51e';
}

.fa-columns:before {
  content: '\f0db';
}

.fa-comment:before {
  content: '\f075';
}

.fa-comment-alt:before {
  content: '\f27a';
}

.fa-comment-dollar:before {
  content: '\f651';
}

.fa-comment-dots:before {
  content: '\f4ad';
}

.fa-comment-medical:before {
  content: '\f7f5';
}

.fa-comment-slash:before {
  content: '\f4b3';
}

.fa-comments:before {
  content: '\f086';
}

.fa-comments-dollar:before {
  content: '\f653';
}

.fa-compact-disc:before {
  content: '\f51f';
}

.fa-compass:before {
  content: '\f14e';
}

.fa-compress:before {
  content: '\f066';
}

.fa-compress-alt:before {
  content: '\f422';
}

.fa-compress-arrows-alt:before {
  content: '\f78c';
}

.fa-concierge-bell:before {
  content: '\f562';
}

.fa-confluence:before {
  content: '\f78d';
}

.fa-connectdevelop:before {
  content: '\f20e';
}

.fa-contao:before {
  content: '\f26d';
}

.fa-cookie:before {
  content: '\f563';
}

.fa-cookie-bite:before {
  content: '\f564';
}

.fa-copy:before {
  content: '\f0c5';
}

.fa-copyright:before {
  content: '\f1f9';
}

.fa-cotton-bureau:before {
  content: '\f89e';
}

.fa-couch:before {
  content: '\f4b8';
}

.fa-cpanel:before {
  content: '\f388';
}

.fa-creative-commons:before {
  content: '\f25e';
}

.fa-creative-commons-by:before {
  content: '\f4e7';
}

.fa-creative-commons-nc:before {
  content: '\f4e8';
}

.fa-creative-commons-nc-eu:before {
  content: '\f4e9';
}

.fa-creative-commons-nc-jp:before {
  content: '\f4ea';
}

.fa-creative-commons-nd:before {
  content: '\f4eb';
}

.fa-creative-commons-pd:before {
  content: '\f4ec';
}

.fa-creative-commons-pd-alt:before {
  content: '\f4ed';
}

.fa-creative-commons-remix:before {
  content: '\f4ee';
}

.fa-creative-commons-sa:before {
  content: '\f4ef';
}

.fa-creative-commons-sampling:before {
  content: '\f4f0';
}

.fa-creative-commons-sampling-plus:before {
  content: '\f4f1';
}

.fa-creative-commons-share:before {
  content: '\f4f2';
}

.fa-creative-commons-zero:before {
  content: '\f4f3';
}

.fa-credit-card:before {
  content: '\f09d';
}

.fa-critical-role:before {
  content: '\f6c9';
}

.fa-crop:before {
  content: '\f125';
}

.fa-crop-alt:before {
  content: '\f565';
}

.fa-cross:before {
  content: '\f654';
}

.fa-crosshairs:before {
  content: '\f05b';
}

.fa-crow:before {
  content: '\f520';
}

.fa-crown:before {
  content: '\f521';
}

.fa-crutch:before {
  content: '\f7f7';
}

.fa-css3:before {
  content: '\f13c';
}

.fa-css3-alt:before {
  content: '\f38b';
}

.fa-cube:before {
  content: '\f1b2';
}

.fa-cubes:before {
  content: '\f1b3';
}

.fa-cut:before {
  content: '\f0c4';
}

.fa-cuttlefish:before {
  content: '\f38c';
}

.fa-d-and-d:before {
  content: '\f38d';
}

.fa-d-and-d-beyond:before {
  content: '\f6ca';
}

.fa-dailymotion:before {
  content: '\e052';
}

.fa-dashcube:before {
  content: '\f210';
}

.fa-database:before {
  content: '\f1c0';
}

.fa-deaf:before {
  content: '\f2a4';
}

.fa-deezer:before {
  content: '\e077';
}

.fa-delicious:before {
  content: '\f1a5';
}

.fa-democrat:before {
  content: '\f747';
}

.fa-deploydog:before {
  content: '\f38e';
}

.fa-deskpro:before {
  content: '\f38f';
}

.fa-desktop:before {
  content: '\f108';
}

.fa-dev:before {
  content: '\f6cc';
}

.fa-deviantart:before {
  content: '\f1bd';
}

.fa-dharmachakra:before {
  content: '\f655';
}

.fa-dhl:before {
  content: '\f790';
}

.fa-diagnoses:before {
  content: '\f470';
}

.fa-diaspora:before {
  content: '\f791';
}

.fa-dice:before {
  content: '\f522';
}

.fa-dice-d20:before {
  content: '\f6cf';
}

.fa-dice-d6:before {
  content: '\f6d1';
}

.fa-dice-five:before {
  content: '\f523';
}

.fa-dice-four:before {
  content: '\f524';
}

.fa-dice-one:before {
  content: '\f525';
}

.fa-dice-six:before {
  content: '\f526';
}

.fa-dice-three:before {
  content: '\f527';
}

.fa-dice-two:before {
  content: '\f528';
}

.fa-digg:before {
  content: '\f1a6';
}

.fa-digital-ocean:before {
  content: '\f391';
}

.fa-digital-tachograph:before {
  content: '\f566';
}

.fa-directions:before {
  content: '\f5eb';
}

.fa-discord:before {
  content: '\f392';
}

.fa-discourse:before {
  content: '\f393';
}

.fa-disease:before {
  content: '\f7fa';
}

.fa-divide:before {
  content: '\f529';
}

.fa-dizzy:before {
  content: '\f567';
}

.fa-dna:before {
  content: '\f471';
}

.fa-dochub:before {
  content: '\f394';
}

.fa-docker:before {
  content: '\f395';
}

.fa-dog:before {
  content: '\f6d3';
}

.fa-dollar-sign:before {
  content: '\f155';
}

.fa-dolly:before {
  content: '\f472';
}

.fa-dolly-flatbed:before {
  content: '\f474';
}

.fa-donate:before {
  content: '\f4b9';
}

.fa-door-closed:before {
  content: '\f52a';
}

.fa-door-open:before {
  content: '\f52b';
}

.fa-dot-circle:before {
  content: '\f192';
}

.fa-dove:before {
  content: '\f4ba';
}

.fa-download:before {
  content: '\f019';
}

.fa-draft2digital:before {
  content: '\f396';
}

.fa-drafting-compass:before {
  content: '\f568';
}

.fa-dragon:before {
  content: '\f6d5';
}

.fa-draw-polygon:before {
  content: '\f5ee';
}

.fa-dribbble:before {
  content: '\f17d';
}

.fa-dribbble-square:before {
  content: '\f397';
}

.fa-dropbox:before {
  content: '\f16b';
}

.fa-drum:before {
  content: '\f569';
}

.fa-drum-steelpan:before {
  content: '\f56a';
}

.fa-drumstick-bite:before {
  content: '\f6d7';
}

.fa-drupal:before {
  content: '\f1a9';
}

.fa-dumbbell:before {
  content: '\f44b';
}

.fa-dumpster:before {
  content: '\f793';
}

.fa-dumpster-fire:before {
  content: '\f794';
}

.fa-dungeon:before {
  content: '\f6d9';
}

.fa-dyalog:before {
  content: '\f399';
}

.fa-earlybirds:before {
  content: '\f39a';
}

.fa-ebay:before {
  content: '\f4f4';
}

.fa-edge:before {
  content: '\f282';
}

.fa-edge-legacy:before {
  content: '\e078';
}

.fa-edit:before {
  content: '\f044';
}

.fa-egg:before {
  content: '\f7fb';
}

.fa-eject:before {
  content: '\f052';
}

.fa-elementor:before {
  content: '\f430';
}

.fa-ellipsis-h:before {
  content: '\f141';
}

.fa-ellipsis-v:before {
  content: '\f142';
}

.fa-ello:before {
  content: '\f5f1';
}

.fa-ember:before {
  content: '\f423';
}

.fa-empire:before {
  content: '\f1d1';
}

.fa-envelope:before {
  content: '\f0e0';
}

.fa-envelope-open:before {
  content: '\f2b6';
}

.fa-envelope-open-text:before {
  content: '\f658';
}

.fa-envelope-square:before {
  content: '\f199';
}

.fa-envira:before {
  content: '\f299';
}

.fa-equals:before {
  content: '\f52c';
}

.fa-eraser:before {
  content: '\f12d';
}

.fa-erlang:before {
  content: '\f39d';
}

.fa-ethereum:before {
  content: '\f42e';
}

.fa-ethernet:before {
  content: '\f796';
}

.fa-etsy:before {
  content: '\f2d7';
}

.fa-euro-sign:before {
  content: '\f153';
}

.fa-evernote:before {
  content: '\f839';
}

.fa-exchange-alt:before {
  content: '\f362';
}

.fa-exclamation:before {
  content: '\f12a';
}

.fa-exclamation-circle:before {
  content: '\f06a';
}

.fa-exclamation-triangle:before {
  content: '\f071';
}

.fa-expand:before {
  content: '\f065';
}

.fa-expand-alt:before {
  content: '\f424';
}

.fa-expand-arrows-alt:before {
  content: '\f31e';
}

.fa-expeditedssl:before {
  content: '\f23e';
}

.fa-external-link-alt:before {
  content: '\f35d';
}

.fa-external-link-square-alt:before {
  content: '\f360';
}

.fa-eye:before {
  content: '\f06e';
}

.fa-eye-dropper:before {
  content: '\f1fb';
}

.fa-eye-slash:before {
  content: '\f070';
}

.fa-facebook:before {
  content: '\f09a';
}

.fa-facebook-f:before {
  content: '\f39e';
}

.fa-facebook-messenger:before {
  content: '\f39f';
}

.fa-facebook-square:before {
  content: '\f082';
}

.fa-fan:before {
  content: '\f863';
}

.fa-fantasy-flight-games:before {
  content: '\f6dc';
}

.fa-fast-backward:before {
  content: '\f049';
}

.fa-fast-forward:before {
  content: '\f050';
}

.fa-faucet:before {
  content: '\e005';
}

.fa-fax:before {
  content: '\f1ac';
}

.fa-feather:before {
  content: '\f52d';
}

.fa-feather-alt:before {
  content: '\f56b';
}

.fa-fedex:before {
  content: '\f797';
}

.fa-fedora:before {
  content: '\f798';
}

.fa-female:before {
  content: '\f182';
}

.fa-fighter-jet:before {
  content: '\f0fb';
}

.fa-figma:before {
  content: '\f799';
}

.fa-file:before {
  content: '\f15b';
}

.fa-file-alt:before {
  content: '\f15c';
}

.fa-file-archive:before {
  content: '\f1c6';
}

.fa-file-audio:before {
  content: '\f1c7';
}

.fa-file-code:before {
  content: '\f1c9';
}

.fa-file-contract:before {
  content: '\f56c';
}

.fa-file-csv:before {
  content: '\f6dd';
}

.fa-file-download:before {
  content: '\f56d';
}

.fa-file-excel:before {
  content: '\f1c3';
}

.fa-file-export:before {
  content: '\f56e';
}

.fa-file-image:before {
  content: '\f1c5';
}

.fa-file-import:before {
  content: '\f56f';
}

.fa-file-invoice:before {
  content: '\f570';
}

.fa-file-invoice-dollar:before {
  content: '\f571';
}

.fa-file-medical:before {
  content: '\f477';
}

.fa-file-medical-alt:before {
  content: '\f478';
}

.fa-file-pdf:before {
  content: '\f1c1';
}

.fa-file-powerpoint:before {
  content: '\f1c4';
}

.fa-file-prescription:before {
  content: '\f572';
}

.fa-file-signature:before {
  content: '\f573';
}

.fa-file-upload:before {
  content: '\f574';
}

.fa-file-video:before {
  content: '\f1c8';
}

.fa-file-word:before {
  content: '\f1c2';
}

.fa-fill:before {
  content: '\f575';
}

.fa-fill-drip:before {
  content: '\f576';
}

.fa-film:before {
  content: '\f008';
}

.fa-filter:before {
  content: '\f0b0';
}

.fa-fingerprint:before {
  content: '\f577';
}

.fa-fire:before {
  content: '\f06d';
}

.fa-fire-alt:before {
  content: '\f7e4';
}

.fa-fire-extinguisher:before {
  content: '\f134';
}

.fa-firefox:before {
  content: '\f269';
}

.fa-firefox-browser:before {
  content: '\e007';
}

.fa-first-aid:before {
  content: '\f479';
}

.fa-first-order:before {
  content: '\f2b0';
}

.fa-first-order-alt:before {
  content: '\f50a';
}

.fa-firstdraft:before {
  content: '\f3a1';
}

.fa-fish:before {
  content: '\f578';
}

.fa-fist-raised:before {
  content: '\f6de';
}

.fa-flag:before {
  content: '\f024';
}

.fa-flag-checkered:before {
  content: '\f11e';
}

.fa-flag-usa:before {
  content: '\f74d';
}

.fa-flask:before {
  content: '\f0c3';
}

.fa-flickr:before {
  content: '\f16e';
}

.fa-flipboard:before {
  content: '\f44d';
}

.fa-flushed:before {
  content: '\f579';
}

.fa-fly:before {
  content: '\f417';
}

.fa-folder:before {
  content: '\f07b';
}

.fa-folder-minus:before {
  content: '\f65d';
}

.fa-folder-open:before {
  content: '\f07c';
}

.fa-folder-plus:before {
  content: '\f65e';
}

.fa-font:before {
  content: '\f031';
}

.fa-font-awesome:before {
  content: '\f2b4';
}

.fa-font-awesome-alt:before {
  content: '\f35c';
}

.fa-font-awesome-flag:before {
  content: '\f425';
}

.fa-font-awesome-logo-full:before {
  content: '\f4e6';
}

.fa-fonticons:before {
  content: '\f280';
}

.fa-fonticons-fi:before {
  content: '\f3a2';
}

.fa-football-ball:before {
  content: '\f44e';
}

.fa-fort-awesome:before {
  content: '\f286';
}

.fa-fort-awesome-alt:before {
  content: '\f3a3';
}

.fa-forumbee:before {
  content: '\f211';
}

.fa-forward:before {
  content: '\f04e';
}

.fa-foursquare:before {
  content: '\f180';
}

.fa-free-code-camp:before {
  content: '\f2c5';
}

.fa-freebsd:before {
  content: '\f3a4';
}

.fa-frog:before {
  content: '\f52e';
}

.fa-frown:before {
  content: '\f119';
}

.fa-frown-open:before {
  content: '\f57a';
}

.fa-fulcrum:before {
  content: '\f50b';
}

.fa-funnel-dollar:before {
  content: '\f662';
}

.fa-futbol:before {
  content: '\f1e3';
}

.fa-galactic-republic:before {
  content: '\f50c';
}

.fa-galactic-senate:before {
  content: '\f50d';
}

.fa-gamepad:before {
  content: '\f11b';
}

.fa-gas-pump:before {
  content: '\f52f';
}

.fa-gavel:before {
  content: '\f0e3';
}

.fa-gem:before {
  content: '\f3a5';
}

.fa-genderless:before {
  content: '\f22d';
}

.fa-get-pocket:before {
  content: '\f265';
}

.fa-gg:before {
  content: '\f260';
}

.fa-gg-circle:before {
  content: '\f261';
}

.fa-ghost:before {
  content: '\f6e2';
}

.fa-gift:before {
  content: '\f06b';
}

.fa-gifts:before {
  content: '\f79c';
}

.fa-git:before {
  content: '\f1d3';
}

.fa-git-alt:before {
  content: '\f841';
}

.fa-git-square:before {
  content: '\f1d2';
}

.fa-github:before {
  content: '\f09b';
}

.fa-github-alt:before {
  content: '\f113';
}

.fa-github-square:before {
  content: '\f092';
}

.fa-gitkraken:before {
  content: '\f3a6';
}

.fa-gitlab:before {
  content: '\f296';
}

.fa-gitter:before {
  content: '\f426';
}

.fa-glass-cheers:before {
  content: '\f79f';
}

.fa-glass-martini:before {
  content: '\f000';
}

.fa-glass-martini-alt:before {
  content: '\f57b';
}

.fa-glass-whiskey:before {
  content: '\f7a0';
}

.fa-glasses:before {
  content: '\f530';
}

.fa-glide:before {
  content: '\f2a5';
}

.fa-glide-g:before {
  content: '\f2a6';
}

.fa-globe:before {
  content: '\f0ac';
}

.fa-globe-africa:before {
  content: '\f57c';
}

.fa-globe-americas:before {
  content: '\f57d';
}

.fa-globe-asia:before {
  content: '\f57e';
}

.fa-globe-europe:before {
  content: '\f7a2';
}

.fa-gofore:before {
  content: '\f3a7';
}

.fa-golf-ball:before {
  content: '\f450';
}

.fa-goodreads:before {
  content: '\f3a8';
}

.fa-goodreads-g:before {
  content: '\f3a9';
}

.fa-google:before {
  content: '\f1a0';
}

.fa-google-drive:before {
  content: '\f3aa';
}

.fa-google-pay:before {
  content: '\e079';
}

.fa-google-play:before {
  content: '\f3ab';
}

.fa-google-plus:before {
  content: '\f2b3';
}

.fa-google-plus-g:before {
  content: '\f0d5';
}

.fa-google-plus-square:before {
  content: '\f0d4';
}

.fa-google-wallet:before {
  content: '\f1ee';
}

.fa-gopuram:before {
  content: '\f664';
}

.fa-graduation-cap:before {
  content: '\f19d';
}

.fa-gratipay:before {
  content: '\f184';
}

.fa-grav:before {
  content: '\f2d6';
}

.fa-greater-than:before {
  content: '\f531';
}

.fa-greater-than-equal:before {
  content: '\f532';
}

.fa-grimace:before {
  content: '\f57f';
}

.fa-grin:before {
  content: '\f580';
}

.fa-grin-alt:before {
  content: '\f581';
}

.fa-grin-beam:before {
  content: '\f582';
}

.fa-grin-beam-sweat:before {
  content: '\f583';
}

.fa-grin-hearts:before {
  content: '\f584';
}

.fa-grin-squint:before {
  content: '\f585';
}

.fa-grin-squint-tears:before {
  content: '\f586';
}

.fa-grin-stars:before {
  content: '\f587';
}

.fa-grin-tears:before {
  content: '\f588';
}

.fa-grin-tongue:before {
  content: '\f589';
}

.fa-grin-tongue-squint:before {
  content: '\f58a';
}

.fa-grin-tongue-wink:before {
  content: '\f58b';
}

.fa-grin-wink:before {
  content: '\f58c';
}

.fa-grip-horizontal:before {
  content: '\f58d';
}

.fa-grip-lines:before {
  content: '\f7a4';
}

.fa-grip-lines-vertical:before {
  content: '\f7a5';
}

.fa-grip-vertical:before {
  content: '\f58e';
}

.fa-gripfire:before {
  content: '\f3ac';
}

.fa-grunt:before {
  content: '\f3ad';
}

.fa-guilded:before {
  content: '\e07e';
}

.fa-guitar:before {
  content: '\f7a6';
}

.fa-gulp:before {
  content: '\f3ae';
}

.fa-h-square:before {
  content: '\f0fd';
}

.fa-hacker-news:before {
  content: '\f1d4';
}

.fa-hacker-news-square:before {
  content: '\f3af';
}

.fa-hackerrank:before {
  content: '\f5f7';
}

.fa-hamburger:before {
  content: '\f805';
}

.fa-hammer:before {
  content: '\f6e3';
}

.fa-hamsa:before {
  content: '\f665';
}

.fa-hand-holding:before {
  content: '\f4bd';
}

.fa-hand-holding-heart:before {
  content: '\f4be';
}

.fa-hand-holding-medical:before {
  content: '\e05c';
}

.fa-hand-holding-usd:before {
  content: '\f4c0';
}

.fa-hand-holding-water:before {
  content: '\f4c1';
}

.fa-hand-lizard:before {
  content: '\f258';
}

.fa-hand-middle-finger:before {
  content: '\f806';
}

.fa-hand-paper:before {
  content: '\f256';
}

.fa-hand-peace:before {
  content: '\f25b';
}

.fa-hand-point-down:before {
  content: '\f0a7';
}

.fa-hand-point-left:before {
  content: '\f0a5';
}

.fa-hand-point-right:before {
  content: '\f0a4';
}

.fa-hand-point-up:before {
  content: '\f0a6';
}

.fa-hand-pointer:before {
  content: '\f25a';
}

.fa-hand-rock:before {
  content: '\f255';
}

.fa-hand-scissors:before {
  content: '\f257';
}

.fa-hand-sparkles:before {
  content: '\e05d';
}

.fa-hand-spock:before {
  content: '\f259';
}

.fa-hands:before {
  content: '\f4c2';
}

.fa-hands-helping:before {
  content: '\f4c4';
}

.fa-hands-wash:before {
  content: '\e05e';
}

.fa-handshake:before {
  content: '\f2b5';
}

.fa-handshake-alt-slash:before {
  content: '\e05f';
}

.fa-handshake-slash:before {
  content: '\e060';
}

.fa-hanukiah:before {
  content: '\f6e6';
}

.fa-hard-hat:before {
  content: '\f807';
}

.fa-hashtag:before {
  content: '\f292';
}

.fa-hat-cowboy:before {
  content: '\f8c0';
}

.fa-hat-cowboy-side:before {
  content: '\f8c1';
}

.fa-hat-wizard:before {
  content: '\f6e8';
}

.fa-hdd:before {
  content: '\f0a0';
}

.fa-head-side-cough:before {
  content: '\e061';
}

.fa-head-side-cough-slash:before {
  content: '\e062';
}

.fa-head-side-mask:before {
  content: '\e063';
}

.fa-head-side-virus:before {
  content: '\e064';
}

.fa-heading:before {
  content: '\f1dc';
}

.fa-headphones:before {
  content: '\f025';
}

.fa-headphones-alt:before {
  content: '\f58f';
}

.fa-headset:before {
  content: '\f590';
}

.fa-heart:before {
  content: '\f004';
}

.fa-heart-broken:before {
  content: '\f7a9';
}

.fa-heartbeat:before {
  content: '\f21e';
}

.fa-helicopter:before {
  content: '\f533';
}

.fa-highlighter:before {
  content: '\f591';
}

.fa-hiking:before {
  content: '\f6ec';
}

.fa-hippo:before {
  content: '\f6ed';
}

.fa-hips:before {
  content: '\f452';
}

.fa-hire-a-helper:before {
  content: '\f3b0';
}

.fa-history:before {
  content: '\f1da';
}

.fa-hive:before {
  content: '\e07f';
}

.fa-hockey-puck:before {
  content: '\f453';
}

.fa-holly-berry:before {
  content: '\f7aa';
}

.fa-home:before {
  content: '\f015';
}

.fa-hooli:before {
  content: '\f427';
}

.fa-hornbill:before {
  content: '\f592';
}

.fa-horse:before {
  content: '\f6f0';
}

.fa-horse-head:before {
  content: '\f7ab';
}

.fa-hospital:before {
  content: '\f0f8';
}

.fa-hospital-alt:before {
  content: '\f47d';
}

.fa-hospital-symbol:before {
  content: '\f47e';
}

.fa-hospital-user:before {
  content: '\f80d';
}

.fa-hot-tub:before {
  content: '\f593';
}

.fa-hotdog:before {
  content: '\f80f';
}

.fa-hotel:before {
  content: '\f594';
}

.fa-hotjar:before {
  content: '\f3b1';
}

.fa-hourglass:before {
  content: '\f254';
}

.fa-hourglass-end:before {
  content: '\f253';
}

.fa-hourglass-half:before {
  content: '\f252';
}

.fa-hourglass-start:before {
  content: '\f251';
}

.fa-house-damage:before {
  content: '\f6f1';
}

.fa-house-user:before {
  content: '\e065';
}

.fa-houzz:before {
  content: '\f27c';
}

.fa-hryvnia:before {
  content: '\f6f2';
}

.fa-html5:before {
  content: '\f13b';
}

.fa-hubspot:before {
  content: '\f3b2';
}

.fa-i-cursor:before {
  content: '\f246';
}

.fa-ice-cream:before {
  content: '\f810';
}

.fa-icicles:before {
  content: '\f7ad';
}

.fa-icons:before {
  content: '\f86d';
}

.fa-id-badge:before {
  content: '\f2c1';
}

.fa-id-card:before {
  content: '\f2c2';
}

.fa-id-card-alt:before {
  content: '\f47f';
}

.fa-ideal:before {
  content: '\e013';
}

.fa-igloo:before {
  content: '\f7ae';
}

.fa-image:before {
  content: '\f03e';
}

.fa-images:before {
  content: '\f302';
}

.fa-imdb:before {
  content: '\f2d8';
}

.fa-inbox:before {
  content: '\f01c';
}

.fa-indent:before {
  content: '\f03c';
}

.fa-industry:before {
  content: '\f275';
}

.fa-infinity:before {
  content: '\f534';
}

.fa-info:before {
  content: '\f129';
}

.fa-info-circle:before {
  content: '\f05a';
}

.fa-innosoft:before {
  content: '\e080';
}

.fa-instagram:before {
  content: '\f16d';
}

.fa-instagram-square:before {
  content: '\e055';
}

.fa-instalod:before {
  content: '\e081';
}

.fa-intercom:before {
  content: '\f7af';
}

.fa-internet-explorer:before {
  content: '\f26b';
}

.fa-invision:before {
  content: '\f7b0';
}

.fa-ioxhost:before {
  content: '\f208';
}

.fa-italic:before {
  content: '\f033';
}

.fa-itch-io:before {
  content: '\f83a';
}

.fa-itunes:before {
  content: '\f3b4';
}

.fa-itunes-note:before {
  content: '\f3b5';
}

.fa-java:before {
  content: '\f4e4';
}

.fa-jedi:before {
  content: '\f669';
}

.fa-jedi-order:before {
  content: '\f50e';
}

.fa-jenkins:before {
  content: '\f3b6';
}

.fa-jira:before {
  content: '\f7b1';
}

.fa-joget:before {
  content: '\f3b7';
}

.fa-joint:before {
  content: '\f595';
}

.fa-joomla:before {
  content: '\f1aa';
}

.fa-journal-whills:before {
  content: '\f66a';
}

.fa-js:before {
  content: '\f3b8';
}

.fa-js-square:before {
  content: '\f3b9';
}

.fa-jsfiddle:before {
  content: '\f1cc';
}

.fa-kaaba:before {
  content: '\f66b';
}

.fa-kaggle:before {
  content: '\f5fa';
}

.fa-key:before {
  content: '\f084';
}

.fa-keybase:before {
  content: '\f4f5';
}

.fa-keyboard:before {
  content: '\f11c';
}

.fa-keycdn:before {
  content: '\f3ba';
}

.fa-khanda:before {
  content: '\f66d';
}

.fa-kickstarter:before {
  content: '\f3bb';
}

.fa-kickstarter-k:before {
  content: '\f3bc';
}

.fa-kiss:before {
  content: '\f596';
}

.fa-kiss-beam:before {
  content: '\f597';
}

.fa-kiss-wink-heart:before {
  content: '\f598';
}

.fa-kiwi-bird:before {
  content: '\f535';
}

.fa-korvue:before {
  content: '\f42f';
}

.fa-landmark:before {
  content: '\f66f';
}

.fa-language:before {
  content: '\f1ab';
}

.fa-laptop:before {
  content: '\f109';
}

.fa-laptop-code:before {
  content: '\f5fc';
}

.fa-laptop-house:before {
  content: '\e066';
}

.fa-laptop-medical:before {
  content: '\f812';
}

.fa-laravel:before {
  content: '\f3bd';
}

.fa-lastfm:before {
  content: '\f202';
}

.fa-lastfm-square:before {
  content: '\f203';
}

.fa-laugh:before {
  content: '\f599';
}

.fa-laugh-beam:before {
  content: '\f59a';
}

.fa-laugh-squint:before {
  content: '\f59b';
}

.fa-laugh-wink:before {
  content: '\f59c';
}

.fa-layer-group:before {
  content: '\f5fd';
}

.fa-leaf:before {
  content: '\f06c';
}

.fa-leanpub:before {
  content: '\f212';
}

.fa-lemon:before {
  content: '\f094';
}

.fa-less:before {
  content: '\f41d';
}

.fa-less-than:before {
  content: '\f536';
}

.fa-less-than-equal:before {
  content: '\f537';
}

.fa-level-down-alt:before {
  content: '\f3be';
}

.fa-level-up-alt:before {
  content: '\f3bf';
}

.fa-life-ring:before {
  content: '\f1cd';
}

.fa-lightbulb:before {
  content: '\f0eb';
}

.fa-line:before {
  content: '\f3c0';
}

.fa-link:before {
  content: '\f0c1';
}

.fa-linkedin:before {
  content: '\f08c';
}

.fa-linkedin-in:before {
  content: '\f0e1';
}

.fa-linode:before {
  content: '\f2b8';
}

.fa-linux:before {
  content: '\f17c';
}

.fa-lira-sign:before {
  content: '\f195';
}

.fa-list:before {
  content: '\f03a';
}

.fa-list-alt:before {
  content: '\f022';
}

.fa-list-ol:before {
  content: '\f0cb';
}

.fa-list-ul:before {
  content: '\f0ca';
}

.fa-location-arrow:before {
  content: '\f124';
}

.fa-lock:before {
  content: '\f023';
}

.fa-lock-open:before {
  content: '\f3c1';
}

.fa-long-arrow-alt-down:before {
  content: '\f309';
}

.fa-long-arrow-alt-left:before {
  content: '\f30a';
}

.fa-long-arrow-alt-right:before {
  content: '\f30b';
}

.fa-long-arrow-alt-up:before {
  content: '\f30c';
}

.fa-low-vision:before {
  content: '\f2a8';
}

.fa-luggage-cart:before {
  content: '\f59d';
}

.fa-lungs:before {
  content: '\f604';
}

.fa-lungs-virus:before {
  content: '\e067';
}

.fa-lyft:before {
  content: '\f3c3';
}

.fa-magento:before {
  content: '\f3c4';
}

.fa-magic:before {
  content: '\f0d0';
}

.fa-magnet:before {
  content: '\f076';
}

.fa-mail-bulk:before {
  content: '\f674';
}

.fa-mailchimp:before {
  content: '\f59e';
}

.fa-male:before {
  content: '\f183';
}

.fa-mandalorian:before {
  content: '\f50f';
}

.fa-map:before {
  content: '\f279';
}

.fa-map-marked:before {
  content: '\f59f';
}

.fa-map-marked-alt:before {
  content: '\f5a0';
}

.fa-map-marker:before {
  content: '\f041';
}

.fa-map-marker-alt:before {
  content: '\f3c5';
}

.fa-map-pin:before {
  content: '\f276';
}

.fa-map-signs:before {
  content: '\f277';
}

.fa-markdown:before {
  content: '\f60f';
}

.fa-marker:before {
  content: '\f5a1';
}

.fa-mars:before {
  content: '\f222';
}

.fa-mars-double:before {
  content: '\f227';
}

.fa-mars-stroke:before {
  content: '\f229';
}

.fa-mars-stroke-h:before {
  content: '\f22b';
}

.fa-mars-stroke-v:before {
  content: '\f22a';
}

.fa-mask:before {
  content: '\f6fa';
}

.fa-mastodon:before {
  content: '\f4f6';
}

.fa-maxcdn:before {
  content: '\f136';
}

.fa-mdb:before {
  content: '\f8ca';
}

.fa-medal:before {
  content: '\f5a2';
}

.fa-medapps:before {
  content: '\f3c6';
}

.fa-medium:before {
  content: '\f23a';
}

.fa-medium-m:before {
  content: '\f3c7';
}

.fa-medkit:before {
  content: '\f0fa';
}

.fa-medrt:before {
  content: '\f3c8';
}

.fa-meetup:before {
  content: '\f2e0';
}

.fa-megaport:before {
  content: '\f5a3';
}

.fa-meh:before {
  content: '\f11a';
}

.fa-meh-blank:before {
  content: '\f5a4';
}

.fa-meh-rolling-eyes:before {
  content: '\f5a5';
}

.fa-memory:before {
  content: '\f538';
}

.fa-mendeley:before {
  content: '\f7b3';
}

.fa-menorah:before {
  content: '\f676';
}

.fa-mercury:before {
  content: '\f223';
}

.fa-meteor:before {
  content: '\f753';
}

.fa-microblog:before {
  content: '\e01a';
}

.fa-microchip:before {
  content: '\f2db';
}

.fa-microphone:before {
  content: '\f130';
}

.fa-microphone-alt:before {
  content: '\f3c9';
}

.fa-microphone-alt-slash:before {
  content: '\f539';
}

.fa-microphone-slash:before {
  content: '\f131';
}

.fa-microscope:before {
  content: '\f610';
}

.fa-microsoft:before {
  content: '\f3ca';
}

.fa-minus:before {
  content: '\f068';
}

.fa-minus-circle:before {
  content: '\f056';
}

.fa-minus-square:before {
  content: '\f146';
}

.fa-mitten:before {
  content: '\f7b5';
}

.fa-mix:before {
  content: '\f3cb';
}

.fa-mixcloud:before {
  content: '\f289';
}

.fa-mixer:before {
  content: '\e056';
}

.fa-mizuni:before {
  content: '\f3cc';
}

.fa-mobile:before {
  content: '\f10b';
}

.fa-mobile-alt:before {
  content: '\f3cd';
}

.fa-modx:before {
  content: '\f285';
}

.fa-monero:before {
  content: '\f3d0';
}

.fa-money-bill:before {
  content: '\f0d6';
}

.fa-money-bill-alt:before {
  content: '\f3d1';
}

.fa-money-bill-wave:before {
  content: '\f53a';
}

.fa-money-bill-wave-alt:before {
  content: '\f53b';
}

.fa-money-check:before {
  content: '\f53c';
}

.fa-money-check-alt:before {
  content: '\f53d';
}

.fa-monument:before {
  content: '\f5a6';
}

.fa-moon:before {
  content: '\f186';
}

.fa-mortar-pestle:before {
  content: '\f5a7';
}

.fa-mosque:before {
  content: '\f678';
}

.fa-motorcycle:before {
  content: '\f21c';
}

.fa-mountain:before {
  content: '\f6fc';
}

.fa-mouse:before {
  content: '\f8cc';
}

.fa-mouse-pointer:before {
  content: '\f245';
}

.fa-mug-hot:before {
  content: '\f7b6';
}

.fa-music:before {
  content: '\f001';
}

.fa-napster:before {
  content: '\f3d2';
}

.fa-neos:before {
  content: '\f612';
}

.fa-network-wired:before {
  content: '\f6ff';
}

.fa-neuter:before {
  content: '\f22c';
}

.fa-newspaper:before {
  content: '\f1ea';
}

.fa-nimblr:before {
  content: '\f5a8';
}

.fa-node:before {
  content: '\f419';
}

.fa-node-js:before {
  content: '\f3d3';
}

.fa-not-equal:before {
  content: '\f53e';
}

.fa-notes-medical:before {
  content: '\f481';
}

.fa-npm:before {
  content: '\f3d4';
}

.fa-ns8:before {
  content: '\f3d5';
}

.fa-nutritionix:before {
  content: '\f3d6';
}

.fa-object-group:before {
  content: '\f247';
}

.fa-object-ungroup:before {
  content: '\f248';
}

.fa-octopus-deploy:before {
  content: '\e082';
}

.fa-odnoklassniki:before {
  content: '\f263';
}

.fa-odnoklassniki-square:before {
  content: '\f264';
}

.fa-oil-can:before {
  content: '\f613';
}

.fa-old-republic:before {
  content: '\f510';
}

.fa-om:before {
  content: '\f679';
}

.fa-opencart:before {
  content: '\f23d';
}

.fa-openid:before {
  content: '\f19b';
}

.fa-opera:before {
  content: '\f26a';
}

.fa-optin-monster:before {
  content: '\f23c';
}

.fa-orcid:before {
  content: '\f8d2';
}

.fa-osi:before {
  content: '\f41a';
}

.fa-otter:before {
  content: '\f700';
}

.fa-outdent:before {
  content: '\f03b';
}

.fa-page4:before {
  content: '\f3d7';
}

.fa-pagelines:before {
  content: '\f18c';
}

.fa-pager:before {
  content: '\f815';
}

.fa-paint-brush:before {
  content: '\f1fc';
}

.fa-paint-roller:before {
  content: '\f5aa';
}

.fa-palette:before {
  content: '\f53f';
}

.fa-palfed:before {
  content: '\f3d8';
}

.fa-pallet:before {
  content: '\f482';
}

.fa-paper-plane:before {
  content: '\f1d8';
}

.fa-paperclip:before {
  content: '\f0c6';
}

.fa-parachute-box:before {
  content: '\f4cd';
}

.fa-paragraph:before {
  content: '\f1dd';
}

.fa-parking:before {
  content: '\f540';
}

.fa-passport:before {
  content: '\f5ab';
}

.fa-pastafarianism:before {
  content: '\f67b';
}

.fa-paste:before {
  content: '\f0ea';
}

.fa-patreon:before {
  content: '\f3d9';
}

.fa-pause:before {
  content: '\f04c';
}

.fa-pause-circle:before {
  content: '\f28b';
}

.fa-paw:before {
  content: '\f1b0';
}

.fa-paypal:before {
  content: '\f1ed';
}

.fa-peace:before {
  content: '\f67c';
}

.fa-pen:before {
  content: '\f304';
}

.fa-pen-alt:before {
  content: '\f305';
}

.fa-pen-fancy:before {
  content: '\f5ac';
}

.fa-pen-nib:before {
  content: '\f5ad';
}

.fa-pen-square:before {
  content: '\f14b';
}

.fa-pencil-alt:before {
  content: '\f303';
}

.fa-pencil-ruler:before {
  content: '\f5ae';
}

.fa-penny-arcade:before {
  content: '\f704';
}

.fa-people-arrows:before {
  content: '\e068';
}

.fa-people-carry:before {
  content: '\f4ce';
}

.fa-pepper-hot:before {
  content: '\f816';
}

.fa-perbyte:before {
  content: '\e083';
}

.fa-percent:before {
  content: '\f295';
}

.fa-percentage:before {
  content: '\f541';
}

.fa-periscope:before {
  content: '\f3da';
}

.fa-person-booth:before {
  content: '\f756';
}

.fa-phabricator:before {
  content: '\f3db';
}

.fa-phoenix-framework:before {
  content: '\f3dc';
}

.fa-phoenix-squadron:before {
  content: '\f511';
}

.fa-phone:before {
  content: '\f095';
}

.fa-phone-alt:before {
  content: '\f879';
}

.fa-phone-slash:before {
  content: '\f3dd';
}

.fa-phone-square:before {
  content: '\f098';
}

.fa-phone-square-alt:before {
  content: '\f87b';
}

.fa-phone-volume:before {
  content: '\f2a0';
}

.fa-photo-video:before {
  content: '\f87c';
}

.fa-php:before {
  content: '\f457';
}

.fa-pied-piper:before {
  content: '\f2ae';
}

.fa-pied-piper-alt:before {
  content: '\f1a8';
}

.fa-pied-piper-hat:before {
  content: '\f4e5';
}

.fa-pied-piper-pp:before {
  content: '\f1a7';
}

.fa-pied-piper-square:before {
  content: '\e01e';
}

.fa-piggy-bank:before {
  content: '\f4d3';
}

.fa-pills:before {
  content: '\f484';
}

.fa-pinterest:before {
  content: '\f0d2';
}

.fa-pinterest-p:before {
  content: '\f231';
}

.fa-pinterest-square:before {
  content: '\f0d3';
}

.fa-pizza-slice:before {
  content: '\f818';
}

.fa-place-of-worship:before {
  content: '\f67f';
}

.fa-plane:before {
  content: '\f072';
}

.fa-plane-arrival:before {
  content: '\f5af';
}

.fa-plane-departure:before {
  content: '\f5b0';
}

.fa-plane-slash:before {
  content: '\e069';
}

.fa-play:before {
  content: '\f04b';
}

.fa-play-circle:before {
  content: '\f144';
}

.fa-playstation:before {
  content: '\f3df';
}

.fa-plug:before {
  content: '\f1e6';
}

.fa-plus:before {
  content: '\f067';
}

.fa-plus-circle:before {
  content: '\f055';
}

.fa-plus-square:before {
  content: '\f0fe';
}

.fa-podcast:before {
  content: '\f2ce';
}

.fa-poll:before {
  content: '\f681';
}

.fa-poll-h:before {
  content: '\f682';
}

.fa-poo:before {
  content: '\f2fe';
}

.fa-poo-storm:before {
  content: '\f75a';
}

.fa-poop:before {
  content: '\f619';
}

.fa-portrait:before {
  content: '\f3e0';
}

.fa-pound-sign:before {
  content: '\f154';
}

.fa-power-off:before {
  content: '\f011';
}

.fa-pray:before {
  content: '\f683';
}

.fa-praying-hands:before {
  content: '\f684';
}

.fa-prescription:before {
  content: '\f5b1';
}

.fa-prescription-bottle:before {
  content: '\f485';
}

.fa-prescription-bottle-alt:before {
  content: '\f486';
}

.fa-print:before {
  content: '\f02f';
}

.fa-procedures:before {
  content: '\f487';
}

.fa-product-hunt:before {
  content: '\f288';
}

.fa-project-diagram:before {
  content: '\f542';
}

.fa-pump-medical:before {
  content: '\e06a';
}

.fa-pump-soap:before {
  content: '\e06b';
}

.fa-pushed:before {
  content: '\f3e1';
}

.fa-puzzle-piece:before {
  content: '\f12e';
}

.fa-python:before {
  content: '\f3e2';
}

.fa-qq:before {
  content: '\f1d6';
}

.fa-qrcode:before {
  content: '\f029';
}

.fa-question:before {
  content: '\f128';
}

.fa-question-circle:before {
  content: '\f059';
}

.fa-quidditch:before {
  content: '\f458';
}

.fa-quinscape:before {
  content: '\f459';
}

.fa-quora:before {
  content: '\f2c4';
}

.fa-quote-left:before {
  content: '\f10d';
}

.fa-quote-right:before {
  content: '\f10e';
}

.fa-quran:before {
  content: '\f687';
}

.fa-r-project:before {
  content: '\f4f7';
}

.fa-radiation:before {
  content: '\f7b9';
}

.fa-radiation-alt:before {
  content: '\f7ba';
}

.fa-rainbow:before {
  content: '\f75b';
}

.fa-random:before {
  content: '\f074';
}

.fa-raspberry-pi:before {
  content: '\f7bb';
}

.fa-ravelry:before {
  content: '\f2d9';
}

.fa-react:before {
  content: '\f41b';
}

.fa-reacteurope:before {
  content: '\f75d';
}

.fa-readme:before {
  content: '\f4d5';
}

.fa-rebel:before {
  content: '\f1d0';
}

.fa-receipt:before {
  content: '\f543';
}

.fa-record-vinyl:before {
  content: '\f8d9';
}

.fa-recycle:before {
  content: '\f1b8';
}

.fa-red-river:before {
  content: '\f3e3';
}

.fa-reddit:before {
  content: '\f1a1';
}

.fa-reddit-alien:before {
  content: '\f281';
}

.fa-reddit-square:before {
  content: '\f1a2';
}

.fa-redhat:before {
  content: '\f7bc';
}

.fa-redo:before {
  content: '\f01e';
}

.fa-redo-alt:before {
  content: '\f2f9';
}

.fa-registered:before {
  content: '\f25d';
}

.fa-remove-format:before {
  content: '\f87d';
}

.fa-renren:before {
  content: '\f18b';
}

.fa-reply:before {
  content: '\f3e5';
}

.fa-reply-all:before {
  content: '\f122';
}

.fa-replyd:before {
  content: '\f3e6';
}

.fa-republican:before {
  content: '\f75e';
}

.fa-researchgate:before {
  content: '\f4f8';
}

.fa-resolving:before {
  content: '\f3e7';
}

.fa-restroom:before {
  content: '\f7bd';
}

.fa-retweet:before {
  content: '\f079';
}

.fa-rev:before {
  content: '\f5b2';
}

.fa-ribbon:before {
  content: '\f4d6';
}

.fa-ring:before {
  content: '\f70b';
}

.fa-road:before {
  content: '\f018';
}

.fa-robot:before {
  content: '\f544';
}

.fa-rocket:before {
  content: '\f135';
}

.fa-rocketchat:before {
  content: '\f3e8';
}

.fa-rockrms:before {
  content: '\f3e9';
}

.fa-route:before {
  content: '\f4d7';
}

.fa-rss:before {
  content: '\f09e';
}

.fa-rss-square:before {
  content: '\f143';
}

.fa-ruble-sign:before {
  content: '\f158';
}

.fa-ruler:before {
  content: '\f545';
}

.fa-ruler-combined:before {
  content: '\f546';
}

.fa-ruler-horizontal:before {
  content: '\f547';
}

.fa-ruler-vertical:before {
  content: '\f548';
}

.fa-running:before {
  content: '\f70c';
}

.fa-rupee-sign:before {
  content: '\f156';
}

.fa-rust:before {
  content: '\e07a';
}

.fa-sad-cry:before {
  content: '\f5b3';
}

.fa-sad-tear:before {
  content: '\f5b4';
}

.fa-safari:before {
  content: '\f267';
}

.fa-salesforce:before {
  content: '\f83b';
}

.fa-sass:before {
  content: '\f41e';
}

.fa-satellite:before {
  content: '\f7bf';
}

.fa-satellite-dish:before {
  content: '\f7c0';
}

.fa-save:before {
  content: '\f0c7';
}

.fa-schlix:before {
  content: '\f3ea';
}

.fa-school:before {
  content: '\f549';
}

.fa-screwdriver:before {
  content: '\f54a';
}

.fa-scribd:before {
  content: '\f28a';
}

.fa-scroll:before {
  content: '\f70e';
}

.fa-sd-card:before {
  content: '\f7c2';
}

.fa-search:before {
  content: '\f002';
}

.fa-search-dollar:before {
  content: '\f688';
}

.fa-search-location:before {
  content: '\f689';
}

.fa-search-minus:before {
  content: '\f010';
}

.fa-search-plus:before {
  content: '\f00e';
}

.fa-searchengin:before {
  content: '\f3eb';
}

.fa-seedling:before {
  content: '\f4d8';
}

.fa-sellcast:before {
  content: '\f2da';
}

.fa-sellsy:before {
  content: '\f213';
}

.fa-server:before {
  content: '\f233';
}

.fa-servicestack:before {
  content: '\f3ec';
}

.fa-shapes:before {
  content: '\f61f';
}

.fa-share:before {
  content: '\f064';
}

.fa-share-alt:before {
  content: '\f1e0';
}

.fa-share-alt-square:before {
  content: '\f1e1';
}

.fa-share-square:before {
  content: '\f14d';
}

.fa-shekel-sign:before {
  content: '\f20b';
}

.fa-shield-alt:before {
  content: '\f3ed';
}

.fa-shield-virus:before {
  content: '\e06c';
}

.fa-ship:before {
  content: '\f21a';
}

.fa-shipping-fast:before {
  content: '\f48b';
}

.fa-shirtsinbulk:before {
  content: '\f214';
}

.fa-shoe-prints:before {
  content: '\f54b';
}

.fa-shopify:before {
  content: '\e057';
}

.fa-shopping-bag:before {
  content: '\f290';
}

.fa-shopping-basket:before {
  content: '\f291';
}

.fa-shopping-cart:before {
  content: '\f07a';
}

.fa-shopware:before {
  content: '\f5b5';
}

.fa-shower:before {
  content: '\f2cc';
}

.fa-shuttle-van:before {
  content: '\f5b6';
}

.fa-sign:before {
  content: '\f4d9';
}

.fa-sign-in-alt:before {
  content: '\f2f6';
}

.fa-sign-language:before {
  content: '\f2a7';
}

.fa-sign-out-alt:before {
  content: '\f2f5';
}

.fa-signal:before {
  content: '\f012';
}

.fa-signature:before {
  content: '\f5b7';
}

.fa-sim-card:before {
  content: '\f7c4';
}

.fa-simplybuilt:before {
  content: '\f215';
}

.fa-sink:before {
  content: '\e06d';
}

.fa-sistrix:before {
  content: '\f3ee';
}

.fa-sitemap:before {
  content: '\f0e8';
}

.fa-sith:before {
  content: '\f512';
}

.fa-skating:before {
  content: '\f7c5';
}

.fa-sketch:before {
  content: '\f7c6';
}

.fa-skiing:before {
  content: '\f7c9';
}

.fa-skiing-nordic:before {
  content: '\f7ca';
}

.fa-skull:before {
  content: '\f54c';
}

.fa-skull-crossbones:before {
  content: '\f714';
}

.fa-skyatlas:before {
  content: '\f216';
}

.fa-skype:before {
  content: '\f17e';
}

.fa-slack:before {
  content: '\f198';
}

.fa-slack-hash:before {
  content: '\f3ef';
}

.fa-slash:before {
  content: '\f715';
}

.fa-sleigh:before {
  content: '\f7cc';
}

.fa-sliders-h:before {
  content: '\f1de';
}

.fa-slideshare:before {
  content: '\f1e7';
}

.fa-smile:before {
  content: '\f118';
}

.fa-smile-beam:before {
  content: '\f5b8';
}

.fa-smile-wink:before {
  content: '\f4da';
}

.fa-smog:before {
  content: '\f75f';
}

.fa-smoking:before {
  content: '\f48d';
}

.fa-smoking-ban:before {
  content: '\f54d';
}

.fa-sms:before {
  content: '\f7cd';
}

.fa-snapchat:before {
  content: '\f2ab';
}

.fa-snapchat-ghost:before {
  content: '\f2ac';
}

.fa-snapchat-square:before {
  content: '\f2ad';
}

.fa-snowboarding:before {
  content: '\f7ce';
}

.fa-snowflake:before {
  content: '\f2dc';
}

.fa-snowman:before {
  content: '\f7d0';
}

.fa-snowplow:before {
  content: '\f7d2';
}

.fa-soap:before {
  content: '\e06e';
}

.fa-socks:before {
  content: '\f696';
}

.fa-solar-panel:before {
  content: '\f5ba';
}

.fa-sort:before {
  content: '\f0dc';
}

.fa-sort-alpha-down:before {
  content: '\f15d';
}

.fa-sort-alpha-down-alt:before {
  content: '\f881';
}

.fa-sort-alpha-up:before {
  content: '\f15e';
}

.fa-sort-alpha-up-alt:before {
  content: '\f882';
}

.fa-sort-amount-down:before {
  content: '\f160';
}

.fa-sort-amount-down-alt:before {
  content: '\f884';
}

.fa-sort-amount-up:before {
  content: '\f161';
}

.fa-sort-amount-up-alt:before {
  content: '\f885';
}

.fa-sort-down:before {
  content: '\f0dd';
}

.fa-sort-numeric-down:before {
  content: '\f162';
}

.fa-sort-numeric-down-alt:before {
  content: '\f886';
}

.fa-sort-numeric-up:before {
  content: '\f163';
}

.fa-sort-numeric-up-alt:before {
  content: '\f887';
}

.fa-sort-up:before {
  content: '\f0de';
}

.fa-soundcloud:before {
  content: '\f1be';
}

.fa-sourcetree:before {
  content: '\f7d3';
}

.fa-spa:before {
  content: '\f5bb';
}

.fa-space-shuttle:before {
  content: '\f197';
}

.fa-speakap:before {
  content: '\f3f3';
}

.fa-speaker-deck:before {
  content: '\f83c';
}

.fa-spell-check:before {
  content: '\f891';
}

.fa-spider:before {
  content: '\f717';
}

.fa-spinner:before {
  content: '\f110';
}

.fa-splotch:before {
  content: '\f5bc';
}

.fa-spotify:before {
  content: '\f1bc';
}

.fa-spray-can:before {
  content: '\f5bd';
}

.fa-square:before {
  content: '\f0c8';
}

.fa-square-full:before {
  content: '\f45c';
}

.fa-square-root-alt:before {
  content: '\f698';
}

.fa-squarespace:before {
  content: '\f5be';
}

.fa-stack-exchange:before {
  content: '\f18d';
}

.fa-stack-overflow:before {
  content: '\f16c';
}

.fa-stackpath:before {
  content: '\f842';
}

.fa-stamp:before {
  content: '\f5bf';
}

.fa-star:before {
  content: '\f005';
}

.fa-star-and-crescent:before {
  content: '\f699';
}

.fa-star-half:before {
  content: '\f089';
}

.fa-star-half-alt:before {
  content: '\f5c0';
}

.fa-star-of-david:before {
  content: '\f69a';
}

.fa-star-of-life:before {
  content: '\f621';
}

.fa-staylinked:before {
  content: '\f3f5';
}

.fa-steam:before {
  content: '\f1b6';
}

.fa-steam-square:before {
  content: '\f1b7';
}

.fa-steam-symbol:before {
  content: '\f3f6';
}

.fa-step-backward:before {
  content: '\f048';
}

.fa-step-forward:before {
  content: '\f051';
}

.fa-stethoscope:before {
  content: '\f0f1';
}

.fa-sticker-mule:before {
  content: '\f3f7';
}

.fa-sticky-note:before {
  content: '\f249';
}

.fa-stop:before {
  content: '\f04d';
}

.fa-stop-circle:before {
  content: '\f28d';
}

.fa-stopwatch:before {
  content: '\f2f2';
}

.fa-stopwatch-20:before {
  content: '\e06f';
}

.fa-store:before {
  content: '\f54e';
}

.fa-store-alt:before {
  content: '\f54f';
}

.fa-store-alt-slash:before {
  content: '\e070';
}

.fa-store-slash:before {
  content: '\e071';
}

.fa-strava:before {
  content: '\f428';
}

.fa-stream:before {
  content: '\f550';
}

.fa-street-view:before {
  content: '\f21d';
}

.fa-strikethrough:before {
  content: '\f0cc';
}

.fa-stripe:before {
  content: '\f429';
}

.fa-stripe-s:before {
  content: '\f42a';
}

.fa-stroopwafel:before {
  content: '\f551';
}

.fa-studiovinari:before {
  content: '\f3f8';
}

.fa-stumbleupon:before {
  content: '\f1a4';
}

.fa-stumbleupon-circle:before {
  content: '\f1a3';
}

.fa-subscript:before {
  content: '\f12c';
}

.fa-subway:before {
  content: '\f239';
}

.fa-suitcase:before {
  content: '\f0f2';
}

.fa-suitcase-rolling:before {
  content: '\f5c1';
}

.fa-sun:before {
  content: '\f185';
}

.fa-superpowers:before {
  content: '\f2dd';
}

.fa-superscript:before {
  content: '\f12b';
}

.fa-supple:before {
  content: '\f3f9';
}

.fa-surprise:before {
  content: '\f5c2';
}

.fa-suse:before {
  content: '\f7d6';
}

.fa-swatchbook:before {
  content: '\f5c3';
}

.fa-swift:before {
  content: '\f8e1';
}

.fa-swimmer:before {
  content: '\f5c4';
}

.fa-swimming-pool:before {
  content: '\f5c5';
}

.fa-symfony:before {
  content: '\f83d';
}

.fa-synagogue:before {
  content: '\f69b';
}

.fa-sync:before {
  content: '\f021';
}

.fa-sync-alt:before {
  content: '\f2f1';
}

.fa-syringe:before {
  content: '\f48e';
}

.fa-table:before {
  content: '\f0ce';
}

.fa-table-tennis:before {
  content: '\f45d';
}

.fa-tablet:before {
  content: '\f10a';
}

.fa-tablet-alt:before {
  content: '\f3fa';
}

.fa-tablets:before {
  content: '\f490';
}

.fa-tachometer-alt:before {
  content: '\f3fd';
}

.fa-tag:before {
  content: '\f02b';
}

.fa-tags:before {
  content: '\f02c';
}

.fa-tape:before {
  content: '\f4db';
}

.fa-tasks:before {
  content: '\f0ae';
}

.fa-taxi:before {
  content: '\f1ba';
}

.fa-teamspeak:before {
  content: '\f4f9';
}

.fa-teeth:before {
  content: '\f62e';
}

.fa-teeth-open:before {
  content: '\f62f';
}

.fa-telegram:before {
  content: '\f2c6';
}

.fa-telegram-plane:before {
  content: '\f3fe';
}

.fa-temperature-high:before {
  content: '\f769';
}

.fa-temperature-low:before {
  content: '\f76b';
}

.fa-tencent-weibo:before {
  content: '\f1d5';
}

.fa-tenge:before {
  content: '\f7d7';
}

.fa-terminal:before {
  content: '\f120';
}

.fa-text-height:before {
  content: '\f034';
}

.fa-text-width:before {
  content: '\f035';
}

.fa-th:before {
  content: '\f00a';
}

.fa-th-large:before {
  content: '\f009';
}

.fa-th-list:before {
  content: '\f00b';
}

.fa-the-red-yeti:before {
  content: '\f69d';
}

.fa-theater-masks:before {
  content: '\f630';
}

.fa-themeco:before {
  content: '\f5c6';
}

.fa-themeisle:before {
  content: '\f2b2';
}

.fa-thermometer:before {
  content: '\f491';
}

.fa-thermometer-empty:before {
  content: '\f2cb';
}

.fa-thermometer-full:before {
  content: '\f2c7';
}

.fa-thermometer-half:before {
  content: '\f2c9';
}

.fa-thermometer-quarter:before {
  content: '\f2ca';
}

.fa-thermometer-three-quarters:before {
  content: '\f2c8';
}

.fa-think-peaks:before {
  content: '\f731';
}

.fa-thumbs-down:before {
  content: '\f165';
}

.fa-thumbs-up:before {
  content: '\f164';
}

.fa-thumbtack:before {
  content: '\f08d';
}

.fa-ticket-alt:before {
  content: '\f3ff';
}

.fa-tiktok:before {
  content: '\e07b';
}

.fa-times:before {
  content: '\f00d';
}

.fa-times-circle:before {
  content: '\f057';
}

.fa-tint:before {
  content: '\f043';
}

.fa-tint-slash:before {
  content: '\f5c7';
}

.fa-tired:before {
  content: '\f5c8';
}

.fa-toggle-off:before {
  content: '\f204';
}

.fa-toggle-on:before {
  content: '\f205';
}

.fa-toilet:before {
  content: '\f7d8';
}

.fa-toilet-paper:before {
  content: '\f71e';
}

.fa-toilet-paper-slash:before {
  content: '\e072';
}

.fa-toolbox:before {
  content: '\f552';
}

.fa-tools:before {
  content: '\f7d9';
}

.fa-tooth:before {
  content: '\f5c9';
}

.fa-torah:before {
  content: '\f6a0';
}

.fa-torii-gate:before {
  content: '\f6a1';
}

.fa-tractor:before {
  content: '\f722';
}

.fa-trade-federation:before {
  content: '\f513';
}

.fa-trademark:before {
  content: '\f25c';
}

.fa-traffic-light:before {
  content: '\f637';
}

.fa-trailer:before {
  content: '\e041';
}

.fa-train:before {
  content: '\f238';
}

.fa-tram:before {
  content: '\f7da';
}

.fa-transgender:before {
  content: '\f224';
}

.fa-transgender-alt:before {
  content: '\f225';
}

.fa-trash:before {
  content: '\f1f8';
}

.fa-trash-alt:before {
  content: '\f2ed';
}

.fa-trash-restore:before {
  content: '\f829';
}

.fa-trash-restore-alt:before {
  content: '\f82a';
}

.fa-tree:before {
  content: '\f1bb';
}

.fa-trello:before {
  content: '\f181';
}

.fa-tripadvisor:before {
  content: '\f262';
}

.fa-trophy:before {
  content: '\f091';
}

.fa-truck:before {
  content: '\f0d1';
}

.fa-truck-loading:before {
  content: '\f4de';
}

.fa-truck-monster:before {
  content: '\f63b';
}

.fa-truck-moving:before {
  content: '\f4df';
}

.fa-truck-pickup:before {
  content: '\f63c';
}

.fa-tshirt:before {
  content: '\f553';
}

.fa-tty:before {
  content: '\f1e4';
}

.fa-tumblr:before {
  content: '\f173';
}

.fa-tumblr-square:before {
  content: '\f174';
}

.fa-tv:before {
  content: '\f26c';
}

.fa-twitch:before {
  content: '\f1e8';
}

.fa-twitter:before {
  content: '\f099';
}

.fa-twitter-square:before {
  content: '\f081';
}

.fa-typo3:before {
  content: '\f42b';
}

.fa-uber:before {
  content: '\f402';
}

.fa-ubuntu:before {
  content: '\f7df';
}

.fa-uikit:before {
  content: '\f403';
}

.fa-umbraco:before {
  content: '\f8e8';
}

.fa-umbrella:before {
  content: '\f0e9';
}

.fa-umbrella-beach:before {
  content: '\f5ca';
}

.fa-uncharted:before {
  content: '\e084';
}

.fa-underline:before {
  content: '\f0cd';
}

.fa-undo:before {
  content: '\f0e2';
}

.fa-undo-alt:before {
  content: '\f2ea';
}

.fa-uniregistry:before {
  content: '\f404';
}

.fa-unity:before {
  content: '\e049';
}

.fa-universal-access:before {
  content: '\f29a';
}

.fa-university:before {
  content: '\f19c';
}

.fa-unlink:before {
  content: '\f127';
}

.fa-unlock:before {
  content: '\f09c';
}

.fa-unlock-alt:before {
  content: '\f13e';
}

.fa-unsplash:before {
  content: '\e07c';
}

.fa-untappd:before {
  content: '\f405';
}

.fa-upload:before {
  content: '\f093';
}

.fa-ups:before {
  content: '\f7e0';
}

.fa-usb:before {
  content: '\f287';
}

.fa-user:before {
  content: '\f007';
}

.fa-user-alt:before {
  content: '\f406';
}

.fa-user-alt-slash:before {
  content: '\f4fa';
}

.fa-user-astronaut:before {
  content: '\f4fb';
}

.fa-user-check:before {
  content: '\f4fc';
}

.fa-user-circle:before {
  content: '\f2bd';
}

.fa-user-clock:before {
  content: '\f4fd';
}

.fa-user-cog:before {
  content: '\f4fe';
}

.fa-user-edit:before {
  content: '\f4ff';
}

.fa-user-friends:before {
  content: '\f500';
}

.fa-user-graduate:before {
  content: '\f501';
}

.fa-user-injured:before {
  content: '\f728';
}

.fa-user-lock:before {
  content: '\f502';
}

.fa-user-md:before {
  content: '\f0f0';
}

.fa-user-minus:before {
  content: '\f503';
}

.fa-user-ninja:before {
  content: '\f504';
}

.fa-user-nurse:before {
  content: '\f82f';
}

.fa-user-plus:before {
  content: '\f234';
}

.fa-user-secret:before {
  content: '\f21b';
}

.fa-user-shield:before {
  content: '\f505';
}

.fa-user-slash:before {
  content: '\f506';
}

.fa-user-tag:before {
  content: '\f507';
}

.fa-user-tie:before {
  content: '\f508';
}

.fa-user-times:before {
  content: '\f235';
}

.fa-users:before {
  content: '\f0c0';
}

.fa-users-cog:before {
  content: '\f509';
}

.fa-users-slash:before {
  content: '\e073';
}

.fa-usps:before {
  content: '\f7e1';
}

.fa-ussunnah:before {
  content: '\f407';
}

.fa-utensil-spoon:before {
  content: '\f2e5';
}

.fa-utensils:before {
  content: '\f2e7';
}

.fa-vaadin:before {
  content: '\f408';
}

.fa-vector-square:before {
  content: '\f5cb';
}

.fa-venus:before {
  content: '\f221';
}

.fa-venus-double:before {
  content: '\f226';
}

.fa-venus-mars:before {
  content: '\f228';
}

.fa-vest:before {
  content: '\e085';
}

.fa-vest-patches:before {
  content: '\e086';
}

.fa-viacoin:before {
  content: '\f237';
}

.fa-viadeo:before {
  content: '\f2a9';
}

.fa-viadeo-square:before {
  content: '\f2aa';
}

.fa-vial:before {
  content: '\f492';
}

.fa-vials:before {
  content: '\f493';
}

.fa-viber:before {
  content: '\f409';
}

.fa-video:before {
  content: '\f03d';
}

.fa-video-slash:before {
  content: '\f4e2';
}

.fa-vihara:before {
  content: '\f6a7';
}

.fa-vimeo:before {
  content: '\f40a';
}

.fa-vimeo-square:before {
  content: '\f194';
}

.fa-vimeo-v:before {
  content: '\f27d';
}

.fa-vine:before {
  content: '\f1ca';
}

.fa-virus:before {
  content: '\e074';
}

.fa-virus-slash:before {
  content: '\e075';
}

.fa-viruses:before {
  content: '\e076';
}

.fa-vk:before {
  content: '\f189';
}

.fa-vnv:before {
  content: '\f40b';
}

.fa-voicemail:before {
  content: '\f897';
}

.fa-volleyball-ball:before {
  content: '\f45f';
}

.fa-volume-down:before {
  content: '\f027';
}

.fa-volume-mute:before {
  content: '\f6a9';
}

.fa-volume-off:before {
  content: '\f026';
}

.fa-volume-up:before {
  content: '\f028';
}

.fa-vote-yea:before {
  content: '\f772';
}

.fa-vr-cardboard:before {
  content: '\f729';
}

.fa-vuejs:before {
  content: '\f41f';
}

.fa-walking:before {
  content: '\f554';
}

.fa-wallet:before {
  content: '\f555';
}

.fa-warehouse:before {
  content: '\f494';
}

.fa-watchman-monitoring:before {
  content: '\e087';
}

.fa-water:before {
  content: '\f773';
}

.fa-wave-square:before {
  content: '\f83e';
}

.fa-waze:before {
  content: '\f83f';
}

.fa-weebly:before {
  content: '\f5cc';
}

.fa-weibo:before {
  content: '\f18a';
}

.fa-weight:before {
  content: '\f496';
}

.fa-weight-hanging:before {
  content: '\f5cd';
}

.fa-weixin:before {
  content: '\f1d7';
}

.fa-whatsapp:before {
  content: '\f232';
}

.fa-whatsapp-square:before {
  content: '\f40c';
}

.fa-wheelchair:before {
  content: '\f193';
}

.fa-whmcs:before {
  content: '\f40d';
}

.fa-wifi:before {
  content: '\f1eb';
}

.fa-wikipedia-w:before {
  content: '\f266';
}

.fa-wind:before {
  content: '\f72e';
}

.fa-window-close:before {
  content: '\f410';
}

.fa-window-maximize:before {
  content: '\f2d0';
}

.fa-window-minimize:before {
  content: '\f2d1';
}

.fa-window-restore:before {
  content: '\f2d2';
}

.fa-windows:before {
  content: '\f17a';
}

.fa-wine-bottle:before {
  content: '\f72f';
}

.fa-wine-glass:before {
  content: '\f4e3';
}

.fa-wine-glass-alt:before {
  content: '\f5ce';
}

.fa-wix:before {
  content: '\f5cf';
}

.fa-wizards-of-the-coast:before {
  content: '\f730';
}

.fa-wodu:before {
  content: '\e088';
}

.fa-wolf-pack-battalion:before {
  content: '\f514';
}

.fa-won-sign:before {
  content: '\f159';
}

.fa-wordpress:before {
  content: '\f19a';
}

.fa-wordpress-simple:before {
  content: '\f411';
}

.fa-wpbeginner:before {
  content: '\f297';
}

.fa-wpexplorer:before {
  content: '\f2de';
}

.fa-wpforms:before {
  content: '\f298';
}

.fa-wpressr:before {
  content: '\f3e4';
}

.fa-wrench:before {
  content: '\f0ad';
}

.fa-x-ray:before {
  content: '\f497';
}

.fa-xbox:before {
  content: '\f412';
}

.fa-xing:before {
  content: '\f168';
}

.fa-xing-square:before {
  content: '\f169';
}

.fa-y-combinator:before {
  content: '\f23b';
}

.fa-yahoo:before {
  content: '\f19e';
}

.fa-yammer:before {
  content: '\f840';
}

.fa-yandex:before {
  content: '\f413';
}

.fa-yandex-international:before {
  content: '\f414';
}

.fa-yarn:before {
  content: '\f7e3';
}

.fa-yelp:before {
  content: '\f1e9';
}

.fa-yen-sign:before {
  content: '\f157';
}

.fa-yin-yang:before {
  content: '\f6ad';
}

.fa-yoast:before {
  content: '\f2b1';
}

.fa-youtube:before {
  content: '\f167';
}

.fa-youtube-square:before {
  content: '\f431';
}

.fa-zhihu:before {
  content: '\f63f';
}

.sr-only {
  border: 0;
  clip: rect(0, 0, 0, 0);
  height: 1px;
  margin: -1px;
  overflow: hidden;
  padding: 0;
  position: absolute;
  width: 1px;
}

.sr-only-focusable:active,
.sr-only-focusable:focus {
  clip: auto;
  height: auto;
  margin: 0;
  overflow: visible;
  position: static;
  width: auto;
}

@font-face {
  font-family: 'Font Awesome 5 Brands';

  font-style: normal;

  font-weight: 400;

  font-display: block;

  src: url(/_nuxt/fonts/fa-brands-400.89a52ae.eot);

  src: url(/_nuxt/fonts/fa-brands-400.89a52ae.eot?#iefix)
      format('embedded-opentype'),
    url(/_nuxt/fonts/fa-brands-400.c1210e5.woff2) format('woff2'),
    url(/_nuxt/fonts/fa-brands-400.329a95a.woff) format('woff'),
    url(/_nuxt/fonts/fa-brands-400.9e13849.ttf) format('truetype'),
    url(/_nuxt/img/fa-brands-400.216edb9.svg#fontawesome) format('svg');
}

.fab {
  font-family: 'Font Awesome 5 Brands';
}

@font-face {
  font-family: 'Font Awesome 5 Free';

  font-style: normal;

  font-weight: 400;

  font-display: block;

  src: url(/_nuxt/fonts/fa-regular-400.4079ae2.eot);

  src: url(/_nuxt/fonts/fa-regular-400.4079ae2.eot?#iefix)
      format('embedded-opentype'),
    url(/_nuxt/fonts/fa-regular-400.68c5af1.woff2) format('woff2'),
    url(/_nuxt/fonts/fa-regular-400.3672264.woff) format('woff'),
    url(/_nuxt/fonts/fa-regular-400.1017bce.ttf) format('truetype'),
    url(/_nuxt/img/fa-regular-400.19e27d3.svg#fontawesome) format('svg');
}

.fab,
.far {
  font-weight: 400;
}

@font-face {
  font-family: 'Font Awesome 5 Free';

  font-style: normal;

  font-weight: 900;

  font-display: block;

  src: url(/_nuxt/fonts/fa-solid-900.efbd5d2.eot);

  src: url(/_nuxt/fonts/fa-solid-900.efbd5d2.eot?#iefix)
      format('embedded-opentype'),
    url(/_nuxt/fonts/fa-solid-900.ada6e6d.woff2) format('woff2'),
    url(/_nuxt/fonts/fa-solid-900.c6ec080.woff) format('woff'),
    url(/_nuxt/fonts/fa-solid-900.07c3313.ttf) format('truetype'),
    url(/_nuxt/img/fa-solid-900.13de59f.svg#fontawesome) format('svg');
}

.fa,
.far,
.fas {
  font-family: 'Font Awesome 5 Free';
}

.fa,
.fas {
  font-weight: 900;
}

.appNuxt {
  min-height: calc(100vh - 480px);
}

.top-header[data-v-450d52fa] {
  border-bottom-width: 1px;
  border-bottom-color: rgba(0, 0, 0, 0.05);
  position: fixed;
  z-index: 99;
  width: 100%;
  background: #fff;
  top: 0;
}
.btn[data-v-450d52fa] {
  border-radius: 24px;
  font-size: 14px;
  padding: 10px;
  font-weight: 700;
  line-height: 1em;
}
.btn.btn-orange[data-v-450d52fa] {
  border: 1px solid #fd4a1f;
  color: #fff !important;
  background-color: #fd4a1f;
}
.btn.btn-white[data-v-450d52fa] {
  border: 1px solid #e5e5e5;
  color: #fd4a1f !important;
}
.fade-enter-active[data-v-450d52fa],
.fade-leave-active[data-v-450d52fa] {
  transition: opacity 0.8s, transform 0.8s;
}
.fade-enter[data-v-450d52fa],
.fade-leave-to[data-v-450d52fa] {
  opacity: 0;
  transform: scale(0.1);
}
@media (max-width: 639px) {
  .sidebar[data-v-450d52fa] {
    z-index: 20;
    height: 100vh;
    width: 100%;
    background: #fff;
    padding-left: 0.5rem;
    padding-right: 0.5rem;
    position: absolute;
    left: 0;
    bottom: 0;
    top: 3.5rem;
  }
  .sidebar nav a[data-v-450d52fa] {
    padding: 25px 0 25px 10%;
    font-size: 18px;
  }
}

.search-results-items.active li.active[data-v-63538b22] {
  border: 1px solid #ccc;
}
.header-search[data-v-63538b22] {
  border: none;
  background-color: #fafafa;
  padding: 0.715em !important;
  height: auto;
  min-height: 0;
  border-radius: 8px;
  font-size: 14px;
  color: #666;
  width: 100%;
  line-height: normal;
}
.search-results[data-v-63538b22] {
  position: absolute;
  z-index: 999;
  background: #fff;
  width: 100%;
  border: 1px solid #e6e6e6;
  padding: 0.5rem;
  border-radius: 0 0 0.5rem 0.5rem;
}
.search-results h4[data-v-63538b22] {
  border-bottom: 1px solid hsla(0, 0%, 90.2%, 0.6784313725490196);
  padding-bottom: 0.5rem;
  margin-bottom: 0.25rem;
}
.search-results li.item[data-v-63538b22] {
  padding: 0.5rem;
}
.search-image-container[data-v-63538b22] {
  width: 48px;
  height: 48px;
  min-height: 48px;
  min-width: 48px;
  max-width: 48px;
  max-height: 48px;
}

.badge-pos[data-v-360acaeb] {
  position: absolute;
  padding: 0.15rem 0.25rem;
  right: 0;
  top: 0;
}

.top-menu li[data-v-7b989da7]:hover {
  opacity: 0.8;
  transition: all 0.4s ease-in-out;
}
.top-menu li:hover.has-submenu[data-v-7b989da7] {
  opacity: 1;
}
.top-menu li:hover ul.submenu[data-v-7b989da7] {
  opacity: 1;
  visibility: visible;
}
.top-menu li[data-v-7b989da7] {
  margin-bottom: 0;
  margin-right: 2px;
  margin-left: 2px;
  position: relative;
  display: flex;
  align-items: stretch;
}
.top-menu li a.has-submenu[data-v-7b989da7]:first-of-type {
  align-items: center;
  display: flex;
}
.top-menu li a.has-submenu[data-v-7b989da7]:first-of-type:after {
  content: '3';
  font-family: 'ElegantIcons';
  speak: none;
  font-style: normal;
  font-weight: 700;
  font-variant: normal;
  text-transform: none;
  line-height: 1;
  display: block;
  -webkit-font-smoothing: antialiased;
  margin-left: 0.5rem;
  color: #fd4a1f;
}
.top-menu li ul.submenuhidden[data-v-7b989da7] {
  visibility: hidden;
  padding: 0 !important;
  border: 1px solid #e5e5e5 !important;
  border-radius: 8px;
  overflow-y: auto;
  max-height: 400px;
  width: auto;
  top: calc(100% - 1px);
  left: 0;
  position: absolute;
}
.top-menu li ul.submenuhidden li[data-v-7b989da7] {
  position: relative;
  border-bottom: 1px solid #e5e5e5 !important;
  padding: 0;
  width: 100%;
  margin: 0;
}
.top-menu li ul.submenuhidden li a[data-v-7b989da7] {
  font-weight: 500 !important;
  padding: 16px 20px;
  width: 200px;
  display: inline-block;
  word-wrap: break-word;
}
.top-menu li ul.submenudesktop[data-v-7b989da7] {
  visibility: hidden;
  opacity: 0;
  left: 0;
  position: absolute;
  z-index: 99;
}
.top-menu li ul.submenudesktop li[data-v-7b989da7] {
  position: relative;
}
.top-menu li ul.submenudesktop li a[data-v-7b989da7] {
  display: inline-block;
}
.top-menu li ul.submenu[data-v-7b989da7] {
  visibility: hidden;
  opacity: 0;
  transition: all 0.2s ease-in-out;
  background: #fff;
  padding: 0 !important;
  border: 1px solid #e5e5e5 !important;
  border-radius: 8px;
  width: auto;
  top: calc(100% - 1px);
  left: 0;
  position: absolute;
  z-index: 99;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}
.top-menu li ul.submenu li[data-v-7b989da7] {
  opacity: 1 !important;
  position: relative;
  border-bottom: 1px solid #e5e5e5 !important;
  padding: 0;
  width: 100%;
  margin: 0;
}
.top-menu li ul.submenu li a[data-v-7b989da7] {
  color: #000 !important;
  font-weight: 500 !important;
  padding: 16px 20px;
  width: 200px;
  display: inline-block;
  word-wrap: break-word;
  cursor: pointer;
}
.top-menu li ul.submenu li a[data-v-7b989da7]:hover {
  background-color: unset !important;
  opacity: 1 !important;
  color: #fd4a1f !important;
  transition: all 0.4s ease-in-out;
}
.top-menu li a[data-v-7b989da7] {
  font-weight: 400 !important;
  border-radius: 24px;
  margin-bottom: 0 !important;
}
.top-menu li a.quiero-vender[data-v-7b989da7] {
  color: #fff !important;
  background: #fd4a1f !important;
  border-bottom: unset !important;
}
@media (max-width: 640px) {
  .top-menu li a.quiero-vender[data-v-7b989da7] {
    margin-top: 20px;
  }
}
.top-menu li a.boitas-te-compro[data-v-7b989da7] {
  background: red;
  color: #fff !important;
}

footer .top-footer {
  background-color: #333 !important;
  width: 100%;
}
footer .widget.widget_nav_menu ul > li,
footer ul.menu-footer li {
  font-size: 14px;
  color: #fff !important;
  line-height: 16px;
  font-weight: 500;
  margin-bottom: 24px;
}
footer .footer-text {
  color: #b2b2b2 !important;
  font-size: 14px;
  text-align: center;
  padding: 2% 0;
  line-height: 24px;
}
footer .footer-image img {
  margin: 0 auto;
  max-width: 200px;
}
footer .whatsapp-button {
  display: flex;
  flex-direction: row;
  position: fixed;
  z-index: 2;
  bottom: 65px;
  right: 1rem;
  max-width: 95vw;
  background: #25d366;
  color: inherit;
  border-radius: 50%;
  box-shadow: 1px 6px 24px 0 rgba(7, 94, 84, 0.24);
  cursor: pointer;
  -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
  will-change: background-color, width;
}
footer .whatsapp-button .icon {
  height: 60px;
  width: 60px;
  background: transparent
    url("data:image/svg+xml;charset=utf-8,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24'%3E%3Cpath fill='%23fff' d='M3.516 3.516c4.686-4.686 12.284-4.686 16.97 0 4.686 4.686 4.686 12.283 0 16.97a12.004 12.004 0 01-13.754 2.299l-5.814.735a.392.392 0 01-.438-.44l.748-5.788A12.002 12.002 0 013.517 3.517zm3.61 17.043l.3.158a9.846 9.846 0 0011.534-1.758c3.843-3.843 3.843-10.074 0-13.918-3.843-3.843-10.075-3.843-13.918 0a9.846 9.846 0 00-1.747 11.554l.16.303-.51 3.942a.196.196 0 00.219.22l3.961-.501zm6.534-7.003l-.933 1.164a9.843 9.843 0 01-3.497-3.495l1.166-.933a.792.792 0 00.23-.94L9.561 6.96a.793.793 0 00-.924-.445 1291.6 1291.6 0 00-2.023.524.797.797 0 00-.588.88 11.754 11.754 0 0010.005 10.005.797.797 0 00.88-.587l.525-2.023a.793.793 0 00-.445-.923L14.6 13.327a.792.792 0 00-.94.23z'/%3E%3C/svg%3E")
    50% no-repeat;
  background-size: 60%;
}
footer .social-media {
  border-radius: 3px;
  padding: 0.5rem;
  margin: auto 0.5rem auto auto;
}
footer .metodos-de-pago {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
}
footer .metodos-de-pago img {
  max-width: 60px;
  margin: 10px;
  height: auto;
}
.stamped-reward-card-button-view:before {
  content: 'VER' !important;
}
[data-campaign-redeemable='true']
  .stamped-reward-card-button-spend:not(.stamped-button-disabled):before {
  content: 'REDIMIR' !important;
}
.stamped-rewards-background {
  background: linear-gradient(135deg, #fd4a1f, #fd4a1f);
}
.stamped-rewards-card {
  box-shadow: 0 4px 15px 0 rgba(0, 0, 0, 0.1), 0 1px 2px 0 rgba(0, 0, 0, 0.1),
    inset 0 2px 0 0 #fd4a1f;
}
.stamped-launcher-button {
  background: linear-gradient(135deg, #fd4a1f, #fd4a1f) !important;
}
.stamped-reward-card-button-earn,
.stamped-reward-card-button-spend,
.stamped-rewards-content-action-button {
  background-color: #fd4a1f !important;
}
.stamped-rewards-window a {
  color: #6774c8;
  text-decoration: none;
}
.stamped-rewards-window a.stamped-rewards-content-button {
  color: #333;
  background: #fff;
}
.Cookie--base .Cookie__button {
  background: #fd4a1f;
  color: #fff;
  border-radius: 24px;
}
.Cookie--base .Cookie__button:hover {
  background: #fd4a1f;
  color: #fff;
}

.spinning {
  transform-origin: 50% 50%;
  -webkit-animation: spinning-right 1s linear infinite;
  animation: spinning-right 1s linear infinite;
}

@-webkit-keyframes spinning-right {
  0% {
    transform: rotate(0deg);
  }

  to {
    transform: rotate(1turn);
  }
}

@keyframes spinning-right {
  0% {
    transform: rotate(0deg);
  }

  to {
    transform: rotate(1turn);
  }
}

@-webkit-keyframes splide-loading {
  0% {
    transform: rotate(0);
  }

  to {
    transform: rotate(1turn);
  }
}

@keyframes splide-loading {
  0% {
    transform: rotate(0);
  }

  to {
    transform: rotate(1turn);
  }
}

.splide__container {
  position: relative;
  box-sizing: border-box;
}

.splide__list {
  margin: 0 !important;
  padding: 0 !important;
  width: -webkit-max-content;
  width: -moz-max-content;
  width: max-content;
  will-change: transform;
}

.splide.is-active .splide__list {
  display: flex;
}

.splide__pagination {
  display: inline-flex;
  align-items: center;
  width: 95%;
  flex-wrap: wrap;
  justify-content: center;
  margin: 0;
}

.splide__pagination li {
  list-style-type: none;
  display: inline-block;
  line-height: 1;
  margin: 0;
}

.splide {
  visibility: hidden;
}

.splide,
.splide__slide {
  position: relative;
  outline: none;
}

.splide__slide {
  box-sizing: border-box;
  list-style-type: none !important;
  margin: 0;
  flex-shrink: 0;
}

.splide__slide img {
  vertical-align: bottom;
}

.splide__slider {
  position: relative;
}

.splide__spinner {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  margin: auto;
  display: inline-block;
  width: 20px;
  height: 20px;
  border-radius: 50%;
  border: 2px solid #999;
  border-left-color: transparent;
  -webkit-animation: splide-loading 1s linear infinite;
  animation: splide-loading 1s linear infinite;
}

.splide__track {
  position: relative;
  z-index: 0;
  overflow: hidden;
}

.splide--draggable > .splide__track > .splide__list > .splide__slide {
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.splide--fade > .splide__track > .splide__list {
  display: block;
}

.splide--fade > .splide__track > .splide__list > .splide__slide {
  position: absolute;
  top: 0;
  left: 0;
  z-index: 0;
  opacity: 0;
}

.splide--fade > .splide__track > .splide__list > .splide__slide.is-active {
  position: relative;
  z-index: 1;
  opacity: 1;
}

.splide--rtl {
  direction: rtl;
}

.splide--ttb > .splide__track > .splide__list {
  display: block;
}

.splide--ttb > .splide__pagination {
  width: auto;
}

.splide__arrow {
  position: absolute;
  z-index: 1;
  top: 50%;
  transform: translateY(-50%);
  width: 2em;
  height: 2em;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  border: none;
  padding: 0;
  opacity: 0.7;
  background: #ccc;
}

.splide__arrow svg {
  width: 1.2em;
  height: 1.2em;
}

.splide__arrow:hover {
  cursor: pointer;
  opacity: 0.9;
}

.splide__arrow:focus {
  outline: none;
}

.splide__arrow--prev {
  left: 1em;
}

.splide__arrow--prev svg {
  transform: scaleX(-1);
}

.splide__arrow--next {
  right: 1em;
}

.splide__pagination {
  position: absolute;
  z-index: 1;
  bottom: 0.5em;
  left: 50%;
  transform: translateX(-50%);
  padding: 0;
}

.splide__pagination__page {
  display: inline-block;
  width: 8px;
  height: 8px;
  background: #ccc;
  border-radius: 50%;
  margin: 3px;
  padding: 0;
  transition: transform 0.2s linear;
  border: none;
  opacity: 0.7;
}

.splide__pagination__page.is-active {
  transform: scale(1.4);
  background: #fff;
}

.splide__pagination__page:hover {
  cursor: pointer;
  opacity: 0.9;
}

.splide__pagination__page:focus {
  outline: none;
}

.splide__progress__bar {
  width: 0;
  height: 3px;
  background: #ccc;
}

.splide--nav > .splide__track > .splide__list > .splide__slide {
  border: 3px solid transparent;
}

.splide--nav > .splide__track > .splide__list > .splide__slide.is-active {
  border-color: #000;
}

.splide--nav > .splide__track > .splide__list > .splide__slide:focus {
  outline: none;
}

.splide--rtl > .splide__arrows .splide__arrow--prev,
.splide--rtl > .splide__track > .splide__arrows .splide__arrow--prev {
  right: 1em;
  left: auto;
}

.splide--rtl > .splide__arrows .splide__arrow--prev svg,
.splide--rtl > .splide__track > .splide__arrows .splide__arrow--prev svg {
  transform: scaleX(1);
}

.splide--rtl > .splide__arrows .splide__arrow--next,
.splide--rtl > .splide__track > .splide__arrows .splide__arrow--next {
  left: 1em;
  right: auto;
}

.splide--rtl > .splide__arrows .splide__arrow--next svg,
.splide--rtl > .splide__track > .splide__arrows .splide__arrow--next svg {
  transform: scaleX(-1);
}

.splide--ttb > .splide__arrows .splide__arrow,
.splide--ttb > .splide__track > .splide__arrows .splide__arrow {
  left: 50%;
  transform: translate(-50%);
}

.splide--ttb > .splide__arrows .splide__arrow--prev,
.splide--ttb > .splide__track > .splide__arrows .splide__arrow--prev {
  top: 1em;
}

.splide--ttb > .splide__arrows .splide__arrow--prev svg,
.splide--ttb > .splide__track > .splide__arrows .splide__arrow--prev svg {
  transform: rotate(-90deg);
}

.splide--ttb > .splide__arrows .splide__arrow--next,
.splide--ttb > .splide__track > .splide__arrows .splide__arrow--next {
  top: auto;
  bottom: 1em;
}

.splide--ttb > .splide__arrows .splide__arrow--next svg,
.splide--ttb > .splide__track > .splide__arrows .splide__arrow--next svg {
  transform: rotate(90deg);
}

.splide--ttb > .splide__pagination {
  display: flex;
  flex-direction: column;
  bottom: 50%;
  left: auto;
  right: 0.5em;
  transform: translateY(50%);
}

@font-face {
  font-family: 'swiper-icons';

  src: url('data:application/font-woff;charset=utf-8;base64, d09GRgABAAAAAAZgABAAAAAADAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABGRlRNAAAGRAAAABoAAAAci6qHkUdERUYAAAWgAAAAIwAAACQAYABXR1BPUwAABhQAAAAuAAAANuAY7+xHU1VCAAAFxAAAAFAAAABm2fPczU9TLzIAAAHcAAAASgAAAGBP9V5RY21hcAAAAkQAAACIAAABYt6F0cBjdnQgAAACzAAAAAQAAAAEABEBRGdhc3AAAAWYAAAACAAAAAj//wADZ2x5ZgAAAywAAADMAAAD2MHtryVoZWFkAAABbAAAADAAAAA2E2+eoWhoZWEAAAGcAAAAHwAAACQC9gDzaG10eAAAAigAAAAZAAAArgJkABFsb2NhAAAC0AAAAFoAAABaFQAUGG1heHAAAAG8AAAAHwAAACAAcABAbmFtZQAAA/gAAAE5AAACXvFdBwlwb3N0AAAFNAAAAGIAAACE5s74hXjaY2BkYGAAYpf5Hu/j+W2+MnAzMYDAzaX6QjD6/4//Bxj5GA8AuRwMYGkAPywL13jaY2BkYGA88P8Agx4j+/8fQDYfA1AEBWgDAIB2BOoAeNpjYGRgYNBh4GdgYgABEMnIABJzYNADCQAACWgAsQB42mNgYfzCOIGBlYGB0YcxjYGBwR1Kf2WQZGhhYGBiYGVmgAFGBiQQkOaawtDAoMBQxXjg/wEGPcYDDA4wNUA2CCgwsAAAO4EL6gAAeNpj2M0gyAACqxgGNWBkZ2D4/wMA+xkDdgAAAHjaY2BgYGaAYBkGRgYQiAHyGMF8FgYHIM3DwMHABGQrMOgyWDLEM1T9/w8UBfEMgLzE////P/5//f/V/xv+r4eaAAeMbAxwIUYmIMHEgKYAYjUcsDAwsLKxc3BycfPw8jEQA/gZBASFhEVExcQlJKWkZWTl5BUUlZRVVNXUNTQZBgMAAMR+E+gAEQFEAAAAKgAqACoANAA+AEgAUgBcAGYAcAB6AIQAjgCYAKIArAC2AMAAygDUAN4A6ADyAPwBBgEQARoBJAEuATgBQgFMAVYBYAFqAXQBfgGIAZIBnAGmAbIBzgHsAAB42u2NMQ6CUAyGW568x9AneYYgm4MJbhKFaExIOAVX8ApewSt4Bic4AfeAid3VOBixDxfPYEza5O+Xfi04YADggiUIULCuEJK8VhO4bSvpdnktHI5QCYtdi2sl8ZnXaHlqUrNKzdKcT8cjlq+rwZSvIVczNiezsfnP/uznmfPFBNODM2K7MTQ45YEAZqGP81AmGGcF3iPqOop0r1SPTaTbVkfUe4HXj97wYE+yNwWYxwWu4v1ugWHgo3S1XdZEVqWM7ET0cfnLGxWfkgR42o2PvWrDMBSFj/IHLaF0zKjRgdiVMwScNRAoWUoH78Y2icB/yIY09An6AH2Bdu/UB+yxopYshQiEvnvu0dURgDt8QeC8PDw7Fpji3fEA4z/PEJ6YOB5hKh4dj3EvXhxPqH/SKUY3rJ7srZ4FZnh1PMAtPhwP6fl2PMJMPDgeQ4rY8YT6Gzao0eAEA409DuggmTnFnOcSCiEiLMgxCiTI6Cq5DZUd3Qmp10vO0LaLTd2cjN4fOumlc7lUYbSQcZFkutRG7g6JKZKy0RmdLY680CDnEJ+UMkpFFe1RN7nxdVpXrC4aTtnaurOnYercZg2YVmLN/d/gczfEimrE/fs/bOuq29Zmn8tloORaXgZgGa78yO9/cnXm2BpaGvq25Dv9S4E9+5SIc9PqupJKhYFSSl47+Qcr1mYNAAAAeNptw0cKwkAAAMDZJA8Q7OUJvkLsPfZ6zFVERPy8qHh2YER+3i/BP83vIBLLySsoKimrqKqpa2hp6+jq6RsYGhmbmJqZSy0sraxtbO3sHRydnEMU4uR6yx7JJXveP7WrDycAAAAAAAH//wACeNpjYGRgYOABYhkgZgJCZgZNBkYGLQZtIJsFLMYAAAw3ALgAeNolizEKgDAQBCchRbC2sFER0YD6qVQiBCv/H9ezGI6Z5XBAw8CBK/m5iQQVauVbXLnOrMZv2oLdKFa8Pjuru2hJzGabmOSLzNMzvutpB3N42mNgZGBg4GKQYzBhYMxJLMlj4GBgAYow/P/PAJJhLM6sSoWKfWCAAwDAjgbRAAB42mNgYGBkAIIbCZo5IPrmUn0hGA0AO8EFTQAA')
    format('woff');

  font-weight: 400;

  font-style: normal;
}

:root {
  --swiper-theme-color: #007aff;
}

.swiper-container {
  margin-left: auto;
  margin-right: auto;
  position: relative;
  overflow: hidden;
  list-style: none;
  padding: 0;
  z-index: 1;
}

.swiper-container-vertical > .swiper-wrapper {
  flex-direction: column;
}

.swiper-wrapper {
  position: relative;
  width: 100%;
  height: 100%;
  z-index: 1;
  display: flex;
  transition-property: transform;
  box-sizing: content-box;
}

.swiper-container-android .swiper-slide,
.swiper-wrapper {
  transform: translateZ(0);
}

.swiper-container-multirow > .swiper-wrapper {
  flex-wrap: wrap;
}

.swiper-container-multirow-column > .swiper-wrapper {
  flex-wrap: wrap;
  flex-direction: column;
}

.swiper-container-free-mode > .swiper-wrapper {
  transition-timing-function: ease-out;
  margin: 0 auto;
}

.swiper-slide {
  flex-shrink: 0;
  width: 100%;
  height: 100%;
  position: relative;
  transition-property: transform;
}

.swiper-slide-invisible-blank {
  visibility: hidden;
}

.swiper-container-autoheight,
.swiper-container-autoheight .swiper-slide {
  height: auto;
}

.swiper-container-autoheight .swiper-wrapper {
  align-items: flex-start;
  transition-property: transform, height;
}

.swiper-container-3d {
  perspective: 1200px;
}

.swiper-container-3d .swiper-cube-shadow,
.swiper-container-3d .swiper-slide,
.swiper-container-3d .swiper-slide-shadow-bottom,
.swiper-container-3d .swiper-slide-shadow-left,
.swiper-container-3d .swiper-slide-shadow-right,
.swiper-container-3d .swiper-slide-shadow-top,
.swiper-container-3d .swiper-wrapper {
  transform-style: preserve-3d;
}

.swiper-container-3d .swiper-slide-shadow-bottom,
.swiper-container-3d .swiper-slide-shadow-left,
.swiper-container-3d .swiper-slide-shadow-right,
.swiper-container-3d .swiper-slide-shadow-top {
  position: absolute;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  pointer-events: none;
  z-index: 10;
}

.swiper-container-3d .swiper-slide-shadow-left {
  background-image: linear-gradient(270deg, rgba(0, 0, 0, 0.5), transparent);
}

.swiper-container-3d .swiper-slide-shadow-right {
  background-image: linear-gradient(90deg, rgba(0, 0, 0, 0.5), transparent);
}

.swiper-container-3d .swiper-slide-shadow-top {
  background-image: linear-gradient(0deg, rgba(0, 0, 0, 0.5), transparent);
}

.swiper-container-3d .swiper-slide-shadow-bottom {
  background-image: linear-gradient(180deg, rgba(0, 0, 0, 0.5), transparent);
}

.swiper-container-css-mode > .swiper-wrapper {
  overflow: auto;
  scrollbar-width: none;
  -ms-overflow-style: none;
}

.swiper-container-css-mode > .swiper-wrapper::-webkit-scrollbar {
  display: none;
}

.swiper-container-css-mode > .swiper-wrapper > .swiper-slide {
  scroll-snap-align: start start;
}

.swiper-container-horizontal.swiper-container-css-mode > .swiper-wrapper {
  scroll-snap-type: x mandatory;
}

.swiper-container-vertical.swiper-container-css-mode > .swiper-wrapper {
  scroll-snap-type: y mandatory;
}

:root {
  --swiper-navigation-size: 44px;
}

.swiper-button-next,
.swiper-button-prev {
  position: absolute;
  top: 50%;
  width: calc(44px / 44 * 27);
  width: calc(var(--swiper-navigation-size) / 44 * 27);
  height: 44px;
  height: var(--swiper-navigation-size);
  margin-top: calc(44px * -1 / 2);
  margin-top: calc(var(--swiper-navigation-size) * -1 / 2);
  z-index: 10;
  cursor: pointer;
  display: flex;
  align-items: center;
  justify-content: center;
  color: var(--swiper-theme-color);
  color: var(--swiper-navigation-color, var(--swiper-theme-color));
}

.swiper-button-next.swiper-button-disabled,
.swiper-button-prev.swiper-button-disabled {
  opacity: 0.35;
  cursor: auto;
  pointer-events: none;
}

.swiper-button-next:after,
.swiper-button-prev:after {
  font-family: swiper-icons;
  font-size: 44px;
  font-size: var(--swiper-navigation-size);
  text-transform: none !important;
  letter-spacing: 0;
  text-transform: none;
  font-variant: normal;
  line-height: 1;
}

.swiper-button-prev,
.swiper-container-rtl .swiper-button-next {
  left: 10px;
  right: auto;
}

.swiper-button-prev:after,
.swiper-container-rtl .swiper-button-next:after {
  content: 'prev';
}

.swiper-button-next,
.swiper-container-rtl .swiper-button-prev {
  right: 10px;
  left: auto;
}

.swiper-button-next:after,
.swiper-container-rtl .swiper-button-prev:after {
  content: 'next';
}

.swiper-button-next.swiper-button-white,
.swiper-button-prev.swiper-button-white {
  --swiper-navigation-color: #fff;
}

.swiper-button-next.swiper-button-black,
.swiper-button-prev.swiper-button-black {
  --swiper-navigation-color: #000;
}

.swiper-button-lock {
  display: none;
}

.swiper-pagination {
  position: absolute;
  text-align: center;
  transition: opacity 0.3s;
  transform: translateZ(0);
  z-index: 10;
}

.swiper-pagination.swiper-pagination-hidden {
  opacity: 0;
}

.swiper-container-horizontal > .swiper-pagination-bullets,
.swiper-pagination-custom,
.swiper-pagination-fraction {
  bottom: 10px;
  left: 0;
  width: 100%;
}

.swiper-pagination-bullets-dynamic {
  overflow: hidden;
  font-size: 0;
}

.swiper-pagination-bullets-dynamic .swiper-pagination-bullet {
  transform: scale(0.33);
  position: relative;
}

.swiper-pagination-bullets-dynamic .swiper-pagination-bullet-active,
.swiper-pagination-bullets-dynamic .swiper-pagination-bullet-active-main {
  transform: scale(1);
}

.swiper-pagination-bullets-dynamic .swiper-pagination-bullet-active-prev {
  transform: scale(0.66);
}

.swiper-pagination-bullets-dynamic .swiper-pagination-bullet-active-prev-prev {
  transform: scale(0.33);
}

.swiper-pagination-bullets-dynamic .swiper-pagination-bullet-active-next {
  transform: scale(0.66);
}

.swiper-pagination-bullets-dynamic .swiper-pagination-bullet-active-next-next {
  transform: scale(0.33);
}

.swiper-pagination-bullet {
  width: 8px;
  height: 8px;
  display: inline-block;
  border-radius: 100%;
  background: #000;
  opacity: 0.2;
}

button.swiper-pagination-bullet {
  border: none;
  margin: 0;
  padding: 0;
  box-shadow: none;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
}

.swiper-pagination-clickable .swiper-pagination-bullet {
  cursor: pointer;
}

.swiper-pagination-bullet-active {
  opacity: 1;
  background: var(--swiper-theme-color);
  background: var(--swiper-pagination-color, var(--swiper-theme-color));
}

.swiper-container-vertical > .swiper-pagination-bullets {
  right: 10px;
  top: 50%;
  transform: translate3d(0, -50%, 0);
}

.swiper-container-vertical
  > .swiper-pagination-bullets
  .swiper-pagination-bullet {
  margin: 6px 0;
  display: block;
}

.swiper-container-vertical
  > .swiper-pagination-bullets.swiper-pagination-bullets-dynamic {
  top: 50%;
  transform: translateY(-50%);
  width: 8px;
}

.swiper-container-vertical
  > .swiper-pagination-bullets.swiper-pagination-bullets-dynamic
  .swiper-pagination-bullet {
  display: inline-block;
  transition: transform 0.2s, top 0.2s;
}

.swiper-container-horizontal
  > .swiper-pagination-bullets
  .swiper-pagination-bullet {
  margin: 0 4px;
}

.swiper-container-horizontal
  > .swiper-pagination-bullets.swiper-pagination-bullets-dynamic {
  left: 50%;
  transform: translateX(-50%);
  white-space: nowrap;
}

.swiper-container-horizontal
  > .swiper-pagination-bullets.swiper-pagination-bullets-dynamic
  .swiper-pagination-bullet {
  transition: transform 0.2s, left 0.2s;
}

.swiper-container-horizontal.swiper-container-rtl
  > .swiper-pagination-bullets-dynamic
  .swiper-pagination-bullet {
  transition: transform 0.2s, right 0.2s;
}

.swiper-pagination-progressbar {
  background: rgba(0, 0, 0, 0.25);
  position: absolute;
}

.swiper-pagination-progressbar .swiper-pagination-progressbar-fill {
  background: var(--swiper-theme-color);
  background: var(--swiper-pagination-color, var(--swiper-theme-color));
  position: absolute;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  transform: scale(0);
  transform-origin: left top;
}

.swiper-container-rtl
  .swiper-pagination-progressbar
  .swiper-pagination-progressbar-fill {
  transform-origin: right top;
}

.swiper-container-horizontal > .swiper-pagination-progressbar,
.swiper-container-vertical
  > .swiper-pagination-progressbar.swiper-pagination-progressbar-opposite {
  width: 100%;
  height: 4px;
  left: 0;
  top: 0;
}

.swiper-container-horizontal
  > .swiper-pagination-progressbar.swiper-pagination-progressbar-opposite,
.swiper-container-vertical > .swiper-pagination-progressbar {
  width: 4px;
  height: 100%;
  left: 0;
  top: 0;
}

.swiper-pagination-white {
  --swiper-pagination-color: #fff;
}

.swiper-pagination-black {
  --swiper-pagination-color: #000;
}

.swiper-pagination-lock {
  display: none;
}

.swiper-scrollbar {
  border-radius: 10px;
  position: relative;
  -ms-touch-action: none;
  background: rgba(0, 0, 0, 0.1);
}

.swiper-container-horizontal > .swiper-scrollbar {
  position: absolute;
  left: 1%;
  bottom: 3px;
  z-index: 50;
  height: 5px;
  width: 98%;
}

.swiper-container-vertical > .swiper-scrollbar {
  position: absolute;
  right: 3px;
  top: 1%;
  z-index: 50;
  width: 5px;
  height: 98%;
}

.swiper-scrollbar-drag {
  height: 100%;
  width: 100%;
  position: relative;
  background: rgba(0, 0, 0, 0.5);
  border-radius: 10px;
  left: 0;
  top: 0;
}

.swiper-scrollbar-cursor-drag {
  cursor: move;
}

.swiper-scrollbar-lock {
  display: none;
}

.swiper-zoom-container {
  width: 100%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.swiper-zoom-container > canvas,
.swiper-zoom-container > img,
.swiper-zoom-container > svg {
  max-width: 100%;
  max-height: 100%;
  object-fit: contain;
}

.swiper-slide-zoomed {
  cursor: move;
}

.swiper-lazy-preloader {
  width: 42px;
  height: 42px;
  position: absolute;
  left: 50%;
  top: 50%;
  margin-left: -21px;
  margin-top: -21px;
  z-index: 10;
  transform-origin: 50%;
  animation: swiper-preloader-spin 1s linear infinite;
  box-sizing: border-box;
  border-radius: 50%;
  border: 4px solid var(--swiper-theme-color);
  border: 4px solid var(--swiper-preloader-color, var(--swiper-theme-color));
  border-top: 4px solid transparent;
}

.swiper-lazy-preloader-white {
  --swiper-preloader-color: #fff;
}

.swiper-lazy-preloader-black {
  --swiper-preloader-color: #000;
}

@keyframes swiper-preloader-spin {
  to {
    transform: rotate(1turn);
  }
}

.swiper-container .swiper-notification {
  position: absolute;
  left: 0;
  top: 0;
  pointer-events: none;
  opacity: 0;
  z-index: -1000;
}

.swiper-container-fade.swiper-container-free-mode .swiper-slide {
  transition-timing-function: ease-out;
}

.swiper-container-fade .swiper-slide {
  pointer-events: none;
  transition-property: opacity;
}

.swiper-container-fade .swiper-slide .swiper-slide {
  pointer-events: none;
}

.swiper-container-fade .swiper-slide-active,
.swiper-container-fade .swiper-slide-active .swiper-slide-active {
  pointer-events: auto;
}

.swiper-container-cube {
  overflow: visible;
}

.swiper-container-cube .swiper-slide {
  pointer-events: none;
  -webkit-backface-visibility: hidden;
  backface-visibility: hidden;
  z-index: 1;
  visibility: hidden;
  transform-origin: 0 0;
  width: 100%;
  height: 100%;
}

.swiper-container-cube .swiper-slide .swiper-slide {
  pointer-events: none;
}

.swiper-container-cube.swiper-container-rtl .swiper-slide {
  transform-origin: 100% 0;
}

.swiper-container-cube .swiper-slide-active,
.swiper-container-cube .swiper-slide-active .swiper-slide-active {
  pointer-events: auto;
}

.swiper-container-cube .swiper-slide-active,
.swiper-container-cube .swiper-slide-next,
.swiper-container-cube .swiper-slide-next + .swiper-slide,
.swiper-container-cube .swiper-slide-prev {
  pointer-events: auto;
  visibility: visible;
}

.swiper-container-cube .swiper-slide-shadow-bottom,
.swiper-container-cube .swiper-slide-shadow-left,
.swiper-container-cube .swiper-slide-shadow-right,
.swiper-container-cube .swiper-slide-shadow-top {
  z-index: 0;
  -webkit-backface-visibility: hidden;
  backface-visibility: hidden;
}

.swiper-container-cube .swiper-cube-shadow {
  position: absolute;
  left: 0;
  bottom: 0;
  width: 100%;
  height: 100%;
  background: #000;
  opacity: 0.6;
  -webkit-filter: blur(50px);
  filter: blur(50px);
  z-index: 0;
}

.swiper-container-flip {
  overflow: visible;
}

.swiper-container-flip .swiper-slide {
  pointer-events: none;
  -webkit-backface-visibility: hidden;
  backface-visibility: hidden;
  z-index: 1;
}

.swiper-container-flip .swiper-slide .swiper-slide {
  pointer-events: none;
}

.swiper-container-flip .swiper-slide-active,
.swiper-container-flip .swiper-slide-active .swiper-slide-active {
  pointer-events: auto;
}

.swiper-container-flip .swiper-slide-shadow-bottom,
.swiper-container-flip .swiper-slide-shadow-left,
.swiper-container-flip .swiper-slide-shadow-right,
.swiper-container-flip .swiper-slide-shadow-top {
  z-index: 0;
  -webkit-backface-visibility: hidden;
  backface-visibility: hidden;
}

.Cookie {
  position: fixed;
  overflow: hidden;
  box-sizing: border-box;
  z-index: 9999;
  width: 100%;
  display: flex;
  justify-content: space-between;
  align-items: baseline;
  flex-direction: column;
}
.Cookie > * {
  margin: 0.9375rem 0;
  align-self: center;
}
@media screen and (min-width: 48rem) {
  .Cookie {
    flex-flow: row;
  }
  .Cookie > * {
    margin: 0;
  }
}
.Cookie--top {
  top: 0;
  left: 0;
  right: 0;
}
.Cookie--bottom {
  bottom: 0;
  left: 0;
  right: 0;
}
.Cookie__buttons {
  display: flex;
  flex-direction: column;
}
.Cookie__buttons > * {
  margin: 0.3125rem 0;
}
@media screen and (min-width: 48rem) {
  .Cookie__buttons {
    flex-direction: row;
  }
  .Cookie__buttons > * {
    margin: 0 0.9375rem;
  }
}
.Cookie__button {
  cursor: pointer;
  align-self: center;
  white-space: nowrap;
}
.Cookie__declineButton {
  cursor: pointer;
  align-self: center;
  white-space: nowrap;
}
.Cookie--base {
  background: #f1f1f1;
  color: #232323;
  padding: 1.25em;
}
.Cookie--base .Cookie__button {
  background: #97d058;
  padding: 0.625em 3.125em;
  color: #fff;
  border-radius: 0;
  border: 0;
  font-size: 1em;
}
.Cookie--base .Cookie__button:hover {
  background: #7ebf36;
}
.Cookie--base .Cookie__button--decline {
  background: transparent;
  padding: 0.625em 3.125em;
  color: #727272;
  border-radius: 0;
  border: 0;
  font-size: 1em;
}
.Cookie--base .Cookie__button--decline:hover {
  background: #cbcbcb;
}
.Cookie--base--rounded {
  background: #f1f1f1;
  color: #232323;
  padding: 1.25em;
}
.Cookie--base--rounded .Cookie__button {
  background: #97d058;
  padding: 0.625em 3.125em;
  color: #fff;
  border-radius: 20px;
  border: 0;
  font-size: 1em;
}
.Cookie--base--rounded .Cookie__button:hover {
  background: #7ebf36;
}
.Cookie--base--rounded .Cookie__button--decline {
  background: transparent;
  padding: 0.625em 3.125em;
  color: #727272;
  border-radius: 20px;
  border: 0;
  font-size: 1em;
}
.Cookie--base--rounded .Cookie__button--decline:hover {
  background: #cbcbcb;
}
.Cookie--blood-orange {
  background: #424851;
  color: #fff;
  padding: 1.25em;
}
.Cookie--blood-orange .Cookie__button {
  background: #e76a68;
  padding: 0.625em 3.125em;
  color: #fff;
  border-radius: 0;
  border: 0;
  font-size: 1em;
}
.Cookie--blood-orange .Cookie__button:hover {
  background: #e03f3c;
}
.Cookie--blood-orange .Cookie__button--decline {
  background: transparent;
  padding: 0.625em 3.125em;
  color: #000;
  border-radius: 0;
  border: 0;
  font-size: 1em;
}
.Cookie--blood-orange .Cookie__button--decline:hover {
  background: #202327;
}
.Cookie--blood-orange--rounded {
  background: #424851;
  color: #fff;
  padding: 1.25em;
}
.Cookie--blood-orange--rounded .Cookie__button {
  background: #e76a68;
  padding: 0.625em 3.125em;
  color: #fff;
  border-radius: 20px;
  border: 0;
  font-size: 1em;
}
.Cookie--blood-orange--rounded .Cookie__button:hover {
  background: #e03f3c;
}
.Cookie--blood-orange--rounded .Cookie__button--decline {
  background: transparent;
  padding: 0.625em 3.125em;
  color: #000;
  border-radius: 20px;
  border: 0;
  font-size: 1em;
}
.Cookie--blood-orange--rounded .Cookie__button--decline:hover {
  background: #202327;
}
.Cookie--dark-lime {
  background: #424851;
  color: #fff;
  padding: 1.25em;
}
.Cookie--dark-lime .Cookie__button {
  background: #97d058;
  padding: 0.625em 3.125em;
  color: #fff;
  border-radius: 0;
  border: 0;
  font-size: 1em;
}
.Cookie--dark-lime .Cookie__button:hover {
  background: #7ebf36;
}
.Cookie--dark-lime .Cookie__button--decline {
  background: transparent;
  padding: 0.625em 3.125em;
  color: #000;
  border-radius: 0;
  border: 0;
  font-size: 1em;
}
.Cookie--dark-lime .Cookie__button--decline:hover {
  background: #202327;
}
.Cookie--dark-lime--rounded {
  background: #424851;
  color: #fff;
  padding: 1.25em;
}
.Cookie--dark-lime--rounded .Cookie__button {
  background: #97d058;
  padding: 0.625em 3.125em;
  color: #fff;
  border-radius: 20px;
  border: 0;
  font-size: 1em;
}
.Cookie--dark-lime--rounded .Cookie__button:hover {
  background: #7ebf36;
}
.Cookie--dark-lime--rounded .Cookie__button--decline {
  background: transparent;
  padding: 0.625em 3.125em;
  color: #000;
  border-radius: 20px;
  border: 0;
  font-size: 1em;
}
.Cookie--dark-lime--rounded .Cookie__button--decline:hover {
  background: #202327;
}
.Cookie--royal {
  background: #fbc227;
  color: #232323;
  padding: 1.25em;
}
.Cookie--royal .Cookie__button {
  background: #726cea;
  padding: 0.625em 3.125em;
  color: #fff;
  border-radius: 0;
  border: 0;
  font-size: 1em;
}
.Cookie--royal .Cookie__button:hover {
  background: #473fe4;
}
.Cookie--royal .Cookie__button--decline {
  background: transparent;
  padding: 0.625em 3.125em;
  color: #221901;
  border-radius: 0;
  border: 0;
  font-size: 1em;
}
.Cookie--royal .Cookie__button--decline:hover {
  background: #d29a04;
}
.Cookie--royal--rounded {
  background: #fbc227;
  color: #232323;
  padding: 1.25em;
}
.Cookie--royal--rounded .Cookie__button {
  background: #726cea;
  padding: 0.625em 3.125em;
  color: #fff;
  border-radius: 20px;
  border: 0;
  font-size: 1em;
}
.Cookie--royal--rounded .Cookie__button:hover {
  background: #473fe4;
}
.Cookie--royal--rounded .Cookie__button--decline {
  background: transparent;
  padding: 0.625em 3.125em;
  color: #221901;
  border-radius: 20px;
  border: 0;
  font-size: 1em;
}
.Cookie--royal--rounded .Cookie__button--decline:hover {
  background: #d29a04;
}
.slideFromTop-enter,
.slideFromTop-leave-to {
  transform: translate(0px, -12.5em);
}
.slideFromTop-enter-to,
.slideFromTop-leave {
  transform: translate(0px, 0px);
}
.slideFromBottom-enter,
.slideFromBottom-leave-to {
  transform: translate(0px, 12.5em);
}
.slideFromBottom-enter-to,
.slideFromBottom-leave {
  transform: translate(0px, 0px);
}
.slideFromBottom-enter-active,
.slideFromBottom-leave-active,
.slideFromTop-enter-active,
.slideFromTop-leave-active {
  transition: transform 0.4s ease-in;
}
.fade-enter-active,
.fade-leave-active {
  transition: opacity 0.5s;
}
.fade-enter,
.fade-leave-to {
  opacity: 0;
}

@keyframes drift-fadeZoomIn {
  0% {
    transform: scale(1.5);
    opacity: 0;
  }
  100% {
    transform: scale(1);
    opacity: 1;
  }
}
@keyframes drift-fadeZoomOut {
  0% {
    transform: scale(1);
    opacity: 1;
  }
  15% {
    transform: scale(1.1);
    opacity: 1;
  }
  100% {
    transform: scale(0.5);
    opacity: 0;
  }
}
@keyframes drift-loader-rotate {
  0% {
    transform: translate(-50%, -50%) rotate(0);
  }
  50% {
    transform: translate(-50%, -50%) rotate(-180deg);
  }
  100% {
    transform: translate(-50%, -50%) rotate(-360deg);
  }
}
@keyframes drift-loader-before {
  0% {
    transform: scale(1);
  }
  10% {
    transform: scale(1.2) translateX(6px);
  }
  25% {
    transform: scale(1.3) translateX(8px);
  }
  40% {
    transform: scale(1.2) translateX(6px);
  }
  50% {
    transform: scale(1);
  }
  60% {
    transform: scale(0.8) translateX(6px);
  }
  75% {
    transform: scale(0.7) translateX(8px);
  }
  90% {
    transform: scale(0.8) translateX(6px);
  }
  100% {
    transform: scale(1);
  }
}
@keyframes drift-loader-after {
  0% {
    transform: scale(1);
  }
  10% {
    transform: scale(1.2) translateX(-6px);
  }
  25% {
    transform: scale(1.3) translateX(-8px);
  }
  40% {
    transform: scale(1.2) translateX(-6px);
  }
  50% {
    transform: scale(1);
  }
  60% {
    transform: scale(0.8) translateX(-6px);
  }
  75% {
    transform: scale(0.7) translateX(-8px);
  }
  90% {
    transform: scale(0.8) translateX(-6px);
  }
  100% {
    transform: scale(1);
  }
}
@-webkit-keyframes drift-fadeZoomIn {
  0% {
    -webkit-transform: scale(1.5);
    opacity: 0;
  }
  100% {
    -webkit-transform: scale(1);
    opacity: 1;
  }
}
@-webkit-keyframes drift-fadeZoomOut {
  0% {
    -webkit-transform: scale(1);
    opacity: 1;
  }
  15% {
    -webkit-transform: scale(1.1);
    opacity: 1;
  }
  100% {
    -webkit-transform: scale(0.5);
    opacity: 0;
  }
}
@-webkit-keyframes drift-loader-rotate {
  0% {
    -webkit-transform: translate(-50%, -50%) rotate(0);
  }
  50% {
    -webkit-transform: translate(-50%, -50%) rotate(-180deg);
  }
  100% {
    -webkit-transform: translate(-50%, -50%) rotate(-360deg);
  }
}
@-webkit-keyframes drift-loader-before {
  0% {
    -webkit-transform: scale(1);
  }
  10% {
    -webkit-transform: scale(1.2) translateX(6px);
  }
  25% {
    -webkit-transform: scale(1.3) translateX(8px);
  }
  40% {
    -webkit-transform: scale(1.2) translateX(6px);
  }
  50% {
    -webkit-transform: scale(1);
  }
  60% {
    -webkit-transform: scale(0.8) translateX(6px);
  }
  75% {
    -webkit-transform: scale(0.7) translateX(8px);
  }
  90% {
    -webkit-transform: scale(0.8) translateX(6px);
  }
  100% {
    -webkit-transform: scale(1);
  }
}
@-webkit-keyframes drift-loader-after {
  0% {
    -webkit-transform: scale(1);
  }
  10% {
    -webkit-transform: scale(1.2) translateX(-6px);
  }
  25% {
    -webkit-transform: scale(1.3) translateX(-8px);
  }
  40% {
    -webkit-transform: scale(1.2) translateX(-6px);
  }
  50% {
    -webkit-transform: scale(1);
  }
  60% {
    -webkit-transform: scale(0.8) translateX(-6px);
  }
  75% {
    -webkit-transform: scale(0.7) translateX(-8px);
  }
  90% {
    -webkit-transform: scale(0.8) translateX(-6px);
  }
  100% {
    -webkit-transform: scale(1);
  }
}
.drift-zoom-pane {
  background: rgba(0, 0, 0, 0.5);
  /* This is required because of a bug that causes border-radius to not
  work with child elements in certain cases. */
  transform: translate3d(0, 0, 0);
  -webkit-transform: translate3d(0, 0, 0);
}
.drift-zoom-pane.drift-opening {
  animation: drift-fadeZoomIn 180ms ease-out;
  -webkit-animation: drift-fadeZoomIn 180ms ease-out;
}
.drift-zoom-pane.drift-closing {
  animation: drift-fadeZoomOut 210ms ease-in;
  -webkit-animation: drift-fadeZoomOut 210ms ease-in;
}
.drift-zoom-pane.drift-inline {
  position: absolute;
  width: 150px;
  height: 150px;
  border-radius: 75px;
  box-shadow: 0 6px 18px rgba(0, 0, 0, 0.3);
}
.drift-loading .drift-zoom-pane-loader {
  display: block;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  -webkit-transform: translate(-50%, -50%);
  width: 66px;
  height: 20px;
  animation: drift-loader-rotate 1800ms infinite linear;
  -webkit-animation: drift-loader-rotate 1800ms infinite linear;
}
.drift-zoom-pane-loader:before,
.drift-zoom-pane-loader:after {
  content: '';
  display: block;
  width: 20px;
  height: 20px;
  position: absolute;
  top: 50%;
  margin-top: -10px;
  border-radius: 20px;
  background: rgba(255, 255, 255, 0.9);
}
.drift-zoom-pane-loader:before {
  left: 0;
  animation: drift-loader-before 1800ms infinite linear;
  -webkit-animation: drift-loader-before 1800ms infinite linear;
}
.drift-zoom-pane-loader:after {
  right: 0;
  animation: drift-loader-after 1800ms infinite linear;
  -webkit-animation: drift-loader-after 1800ms infinite linear;
  animation-delay: -900ms;
  -webkit-animation-delay: -900ms;
}
.drift-bounding-box {
  background-color: rgba(0, 0, 0, 0.4);
}

.scroller-at-top[data-v-033bd07e] {
  display: grid;
  grid-gap: 2px;
  grid-template-columns: 1fr;
  align-items: center;
}
.scroller-at-top .preview-box[data-v-033bd07e] {
  grid-column: 1 / 2;
  grid-row: 2 / 3;
}
.scroller-at-top .thumb-list[data-v-033bd07e] {
  display: grid;
  align-items: center;
  grid-column-gap: 0.2em;
  grid-column: 1 / 2;
  grid-row: 1 / 2;
  visibility: hidden;
}
.scroller-at-bottom[data-v-033bd07e] {
  display: grid;
  grid-gap: 2px;
  grid-template-columns: 1fr;
  align-items: center;
}
.scroller-at-bottom .preview-box[data-v-033bd07e] {
  grid-column: 1 / 2;
  grid-row: 1 / 2;
}
.scroller-at-bottom .thumb-list[data-v-033bd07e] {
  display: grid;
  align-items: center;
  grid-column-gap: 0.2em;
  grid-column: 1 / 2;
  grid-row: 2 / 3;
  visibility: hidden;
}
.scroller-at-left[data-v-033bd07e] {
  display: grid;
  grid-gap: 2px;
  grid-template-columns: 1fr;
}
.scroller-at-left .preview-box[data-v-033bd07e] {
  grid-column: 2 / 3;
  grid-row: 1 / 2;
}
.scroller-at-left .thumb-list[data-v-033bd07e] {
  display: grid;
  grid-row-gap: 0.2em;
  grid-column: 1 / 2;
  grid-row: 1 / 2;
  visibility: hidden;
  justify-items: center;
}
.scroller-at-right[data-v-033bd07e] {
  display: grid;
  grid-gap: 2px;
  grid-template-columns: 1fr;
}
.scroller-at-right .preview-box[data-v-033bd07e] {
  grid-column: 1 / 2;
  grid-row: 1 / 2;
}
.scroller-at-right .thumb-list[data-v-033bd07e] {
  display: grid;
  grid-row-gap: 0.2em;
  grid-column: 2 / 3;
  grid-row: 1 / 2;
  visibility: hidden;
  justify-items: center;
}
.scroller-at-right .thumb-list .responsive-image[data-v-033bd07e],
.scroller-at-left .thumb-list .responsive-image[data-v-033bd07e] {
  width: auto;
  height: 100%;
}
.scroller-at-top .thumb-list .responsive-image[data-v-033bd07e],
.scroller-at-bottom .thumb-list .responsive-image[data-v-033bd07e] {
  height: auto;
  width: 100%;
}
.zoomer-control[data-v-033bd07e] {
  cursor: pointer;
}
.choosed-thumb[data-v-033bd07e] {
  border-radius: 0px;
}
.pane-container[data-v-033bd07e] {
  display: none;
  position: absolute;
  z-index: 10000;
  pointer-events: none;
}

.vue-form-wizard .wizard-btn {
  display: inline-block;
  margin-bottom: 0;
  font-weight: 400;
  text-align: center;
  vertical-align: middle;
  -ms-touch-action: manipulation;
  touch-action: manipulation;
  cursor: pointer;
  background-image: none;
  border: 1px solid transparent;
  white-space: nowrap;
  padding: 6px 12px;
  font-size: 14px;
  line-height: 1.42857;
  border-radius: 4px;
}

.vue-form-wizard .wizard-btn.disabled,
.vue-form-wizard .wizard-btn[disabled],
fieldset[disabled] .vue-form-wizard .wizard-btn {
  cursor: not-allowed;
  opacity: 0.65;
  filter: alpha(opacity=65);
  -webkit-box-shadow: none;
  box-shadow: none;
}

.vue-form-wizard * {
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
}

.vue-form-wizard a {
  text-decoration: none;
}

.vue-form-wizard .wizard-nav {
  margin-bottom: 0;
  padding-left: 0;
  list-style: none;
}

.vue-form-wizard .wizard-nav > li {
  position: relative;
  display: block;
}

.vue-form-wizard .wizard-nav > li > a {
  position: relative;
  display: block;
  padding: 10px 15px;
}

.vue-form-wizard .wizard-nav > li > a:focus,
.vue-form-wizard .wizard-nav > li > a:hover {
  text-decoration: none;
  background-color: #eee;
}

.vue-form-wizard .wizard-nav > li.disabled > a {
  color: #777;
}

.vue-form-wizard .wizard-nav > li.disabled > a:focus,
.vue-form-wizard .wizard-nav > li.disabled > a:hover {
  color: #777;
  text-decoration: none;
  background-color: transparent;
  cursor: not-allowed;
}

.vue-form-wizard .wizard-progress-bar {
  float: left;
  width: 0;
  height: 100%;
  font-size: 12px;
  line-height: 20px;
  color: #fff;
  text-align: center;
  background-color: #337ab7;
  -webkit-box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15);
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15);
  -webkit-transition: width 0.6s ease;
  transition: width 0.6s ease;
}

.vue-form-wizard .navbar .navbar-nav > li > a.wizard-btn,
.vue-form-wizard .wizard-btn {
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
  border-width: 2px;
  background-color: transparent;
  font-size: 14px;
  font-weight: 600;
  padding: 6px 12px;
  min-width: 140px;
}

.vue-form-wizard .navbar .navbar-nav > li > a.wizard-btn:focus,
.vue-form-wizard .navbar .navbar-nav > li > a.wizard-btn:hover,
.vue-form-wizard .wizard-btn:focus,
.vue-form-wizard .wizard-btn:hover {
  outline: 0 !important;
}

.vue-form-wizard .wizard-nav-pills {
  margin-top: 0;
  position: relative;
  text-align: center;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
}

.vue-form-wizard .wizard-nav-pills a,
.vue-form-wizard .wizard-nav-pills li {
  -webkit-box-flex: 1;
  -ms-flex: 1;
  flex: 1;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  -ms-flex-positive: 1;
  flex-grow: 1;
}

.vue-form-wizard .wizard-nav-pills > li > a,
.vue-form-wizard .wizard-nav-pills a {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
}

.vue-form-wizard .wizard-nav-pills > li > a {
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -ms-flex-direction: column;
  flex-direction: column;
  padding: 0;
  margin: 0 auto;
  color: rgba(0, 0, 0, 0.2);
  position: relative;
  top: 3px;
}

.vue-form-wizard .wizard-nav-pills > li > a:focus,
.vue-form-wizard .wizard-nav-pills > li > a:hover {
  background-color: transparent;
  color: rgba(0, 0, 0, 0.2);
  outline: 0 !important;
}

.vue-form-wizard .wizard-nav-pills > li > a.disabled {
  pointer-events: none;
  cursor: default;
}

.vue-form-wizard .wizard-nav-pills > li.active > a,
.vue-form-wizard .wizard-nav-pills > li.active > a:focus,
.vue-form-wizard .wizard-nav-pills > li.active > a:hover {
  background-color: transparent;
  -webkit-transition: font-size 0.2s linear;
  transition: font-size 0.2s linear;
}

.vue-form-wizard .wizard-nav-pills > li.active > a .wizard-icon,
.vue-form-wizard .wizard-nav-pills > li.active > a:focus .wizard-icon,
.vue-form-wizard .wizard-nav-pills > li.active > a:hover .wizard-icon {
  color: #fff;
  font-size: 24px;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-box-pack: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-transition: all 0.2s linear;
  transition: all 0.2s linear;
}

.vue-form-wizard {
  padding-bottom: 20px;
}

.vue-form-wizard .is_error {
  border-color: #c84513 !important;
}

.vue-form-wizard .is_error .icon-container {
  background: #c84513 !important;
}

.vue-form-wizard.xs .wizard-icon-circle {
  width: 40px;
  height: 40px;
  font-size: 16px;
}

.vue-form-wizard.xs .wizard-icon-circle.tab_shape {
  height: 25px;
}

.vue-form-wizard.xs .wizard-nav-pills > li.active > a .wizard-icon {
  font-size: 16px;
}

.vue-form-wizard.xs .wizard-navigation .wizard-progress-with-circle {
  position: relative;
  top: 25px;
  height: 4px;
}

.vue-form-wizard.sm .wizard-icon-circle {
  width: 50px;
  height: 50px;
  font-size: 20px;
}

.vue-form-wizard.sm .wizard-icon-circle.tab_shape {
  height: 30px;
}

.vue-form-wizard.sm .wizard-nav-pills > li.active > a .wizard-icon {
  font-size: 20px;
}

.vue-form-wizard.sm .wizard-navigation .wizard-progress-with-circle {
  position: relative;
  top: 30px;
  height: 4px;
}

.vue-form-wizard.md .wizard-icon-circle {
  width: 70px;
  height: 70px;
  font-size: 24px;
}

.vue-form-wizard.md .wizard-icon-circle.tab_shape {
  height: 40px;
}

.vue-form-wizard.md .wizard-nav-pills > li.active > a .wizard-icon {
  font-size: 24px;
}

.vue-form-wizard.md .wizard-navigation .wizard-progress-with-circle {
  position: relative;
  top: 40px;
  height: 4px;
}

.vue-form-wizard.lg .wizard-icon-circle {
  width: 90px;
  height: 90px;
  font-size: 28px;
}

.vue-form-wizard.lg .wizard-icon-circle.tab_shape {
  height: 50px;
}

.vue-form-wizard.lg .wizard-nav-pills > li.active > a .wizard-icon {
  font-size: 28px;
}

.vue-form-wizard.lg .wizard-navigation .wizard-progress-with-circle {
  position: relative;
  top: 50px;
  height: 4px;
}

.vue-form-wizard .wizard-icon-circle {
  font-size: 18px;
  border: 3px solid #f3f2ee;
  border-radius: 50%;
  font-weight: 600;
  width: 70px;
  height: 70px;
  background-color: #fff;
  position: relative;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: center;
  -ms-flex-pack: center;
  justify-content: center;
  -ms-flex-line-pack: center;
  align-content: center;
}

.vue-form-wizard .wizard-icon-circle.square_shape {
  border-radius: 0;
}

.vue-form-wizard .wizard-icon-circle.tab_shape {
  width: 100%;
  min-width: 100px;
  height: 40px;
  border: none;
  background-color: #f3f2ee;
  border-radius: 0;
}

.vue-form-wizard .wizard-icon-circle .wizard-icon-container {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-flex: 1;
  -ms-flex: 1;
  flex: 1;
  border-radius: 40%;
}

.vue-form-wizard .wizard-icon-circle .wizard-icon-container.square_shape,
.vue-form-wizard .wizard-icon-circle .wizard-icon-container.tab_shape {
  border-radius: 0;
}

.vue-form-wizard .wizard-icon-circle .wizard-icon {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-box-pack: center;
  -ms-flex-pack: center;
  justify-content: center;
}

.vue-form-wizard .wizard-tab-content {
  min-height: 100px;
  padding: 30px 20px 10px;
}

.vue-form-wizard .wizard-header {
  padding: 15px;
  position: relative;
  border-radius: 3px 3px 0 0;
  text-align: center;
}

.vue-form-wizard .wizard-title {
  color: #252422;
  font-weight: 300;
  margin: 0;
  text-align: center;
}

.vue-form-wizard .category {
  font-size: 14px;
  font-weight: 400;
  color: #9a9a9a;
  margin-bottom: 0;
  text-align: center;
}

.vue-form-wizard .wizard-navigation .wizard-progress-with-circle {
  position: relative;
  top: 40px;
  height: 4px;
}

.vue-form-wizard
  .wizard-navigation
  .wizard-progress-with-circle
  .wizard-progress-bar {
  -webkit-box-shadow: none;
  box-shadow: none;
  -webkit-transition: width 0.3s ease;
  transition: width 0.3s ease;
}

.vue-form-wizard .clearfix:after {
  content: '';
  clear: both;
  display: table;
}

.vue-form-wizard .wizard-card-footer {
  padding: 0 20px;
}

.vue-form-wizard .wizard-card-footer .wizard-footer-left {
  float: left;
}

.vue-form-wizard .wizard-card-footer .wizard-footer-right {
  float: right;
}

@media screen and (max-width: 350px) {
  .vue-form-wizard .wizard-card-footer {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-pack: center;
    -ms-flex-pack: center;
    justify-content: center;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -ms-flex-direction: column;
    flex-direction: column;
  }

  .vue-form-wizard .wizard-card-footer .wizard-footer-left,
  .vue-form-wizard .wizard-card-footer .wizard-footer-right {
    float: none;
    -webkit-box-flex: 1;
    -ms-flex: 1;
    flex: 1;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-pack: center;
    -ms-flex-pack: center;
    justify-content: center;
  }

  .vue-form-wizard .wizard-card-footer .wizard-footer-right button {
    margin-top: 10px;
  }
}

.vue-form-wizard.vertical .wizard-card-footer {
  display: block;
}

.vue-form-wizard.vertical .wizard-nav-pills {
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -ms-flex-direction: column;
  flex-direction: column;
}

.vue-form-wizard.vertical .wizard-navigation {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: horizontal;
  -webkit-box-direction: normal;
  -ms-flex-direction: row;
  flex-direction: row;
}

.vue-form-wizard.vertical .wizard-card-footer {
  padding-top: 30px;
}

.product[data-v-616c2587] {
  transition-duration: 0.6s;
}
.product .product-image[data-v-616c2587] {
  border-radius: 6px;
  border: 1px solid #e5e5e5 !important;
  margin-bottom: 9px;
  box-shadow: 1px 2px 3px 0 rgba(0, 0, 0, 0.1);
}
.product .product-image img[data-v-616c2587] {
  border-radius: 6px;
  height: 200px;
  -o-object-fit: contain;
  object-fit: contain;
}
.product .product-content h2[data-v-616c2587] {
  display: -webkit-box;
  overflow: hidden;
  padding: 0 !important;
  -webkit-line-clamp: 2;
  -webkit-box-orient: vertical;
  font-size: 16px;
  color: #000031;
  line-height: 16px;
}
.product .product-content .sending[data-v-616c2587] {
  color: #21bf5c;
  font-family: 'DM Sans', Helvetica, Arial, Lucida, sans-serif;
  font-size: 14px;
  font-weight: 400;
}
.product .product-content .cost[data-v-616c2587] {
  font-size: 16px;
  font-weight: 700;
}
.product[data-v-616c2587]:hover {
  border-radius: 6px;
  box-shadow: 1px 1px 4px 4px rgba(0, 0, 0, 0.07);
}

.swiper-slide img[data-v-dd1fafb6] {
  border-radius: 16px;
  -o-object-fit: cover;
  object-fit: cover;
  width: 100%;
  height: 450px;
  max-height: 100%;
}
.swiper-button-next[data-v-dd1fafb6],
.swiper-button-prev[data-v-dd1fafb6] {
  color: #fff !important;
  background: #fd4a1f !important;
  border-radius: 50%;
  font-size: 14px;
  height: 2.5rem;
  width: 2.5rem;
  opacity: 0.8;
  transition: opacity 0.5s;
}
.swiper-button-next[data-v-dd1fafb6]:hover,
.swiper-button-prev[data-v-dd1fafb6]:hover {
  opacity: 1;
}
.swiper-button-next[data-v-dd1fafb6]:after,
.swiper-button-prev[data-v-dd1fafb6]:after {
  font-size: 1.2rem;
}
@media (max-width: 640px) {
  .swiper-slide img[data-v-dd1fafb6] {
    max-height: 225px;
    border-radius: 0;
  }
  .swiper-button-next[data-v-dd1fafb6],
  .swiper-button-prev[data-v-dd1fafb6] {
    display: none !important;
  }
}

.category-container[data-v-9c3aac16] {
  margin-bottom: 30px;
}
.category-container .category-title h4[data-v-9c3aac16] {
  font-weight: 700;
  font-size: 18px;
  color: #333;
  line-height: 1em;
}
.category-container .category-title a[data-v-9c3aac16] {
  border: 1px solid #e5e5e5;
  padding: 8px 12px;
  border-radius: 24px;
  color: #fd4a1f;
  margin-left: 10px;
  font-size: 14px;
  line-height: 16px;
}
.swiper-container .swiper-slide[data-v-9c3aac16] {
  max-width: 150px;
}

@media screen and (max-width: 640px) {
  .wizard-nav.wizard-nav-pills,
  .wizard-progress-with-circle {
    display: none;
  }
  .wizard-tab-content {
    padding-top: 0 !important;
  }
}

.product-cart[data-v-50bc8256] {
  border-bottom: 1px solid #e5e5e5;
  margin-bottom: 32px;
  padding-bottom: 22px;
}
.product-cart[data-v-50bc8256]:last-child {
  border-bottom: none;
  padding-bottom: 0;
  margin-bottom: 0;
}
.checkout[data-v-50bc8256] {
  background-color: #fd4a1f !important;
  border-color: #fd4a1f !important;
  font-size: 20px;
}
.container-quantity[data-v-50bc8256] {
  margin-right: 0.5rem;
}
.container-quantity .minus[data-v-50bc8256] {
  outline: 0;
  background: 0 0;
  border-radius: 50%;
  font-size: 18px;
  line-height: 1;
  width: 43px;
  height: 43px;
  border: 1px solid #e5e5e5;
}
.container-quantity span[data-v-50bc8256] {
  background: #fff !important;
  color: #000 !important;
  width: 54px;
  border: 1px solid #e5e5e5 !important;
  border-radius: 24px;
  text-align: center !important;
  max-height: 43px;
  margin: 0;
  font-size: 20px;
  font-weight: 500;
  padding: 0.25rem 0;
}
.container-quantity .plus[data-v-50bc8256] {
  outline: 0;
  background: 0 0;
  border-radius: 50%;
  font-size: 18px;
  line-height: 1;
  width: 43px;
  height: 43px;
  border: 1px solid #e5e5e5;
  color: #fd4a1f;
}

.formulate-input[data-classification='box'] .formulate-input-wrapper {
  display: flex;
  align-items: center;
}
.formulate-input[data-classification='box'] .formulate-input-label--after {
  --tw-space-x-reverse: 0;
  margin-right: calc(0.5rem * var(--tw-space-x-reverse));
  margin-left: calc(0.5rem * (1 - var(--tw-space-x-reverse)));
}

.container-add-cart[data-v-435b3f04] {
  display: flex;
  margin-bottom: 0.5rem;
}
.container-add-cart .container-quantity[data-v-435b3f04] {
  margin-right: 0.5rem;
}
.container-add-cart .container-quantity .minus[data-v-435b3f04] {
  outline: 0;
  background: 0 0;
  border-radius: 50%;
  font-size: 18px;
  line-height: 1;
  width: 43px;
  height: 43px;
  border: 1px solid #e5e5e5;
}
.container-add-cart .container-quantity span[data-v-435b3f04] {
  background: #fff !important;
  color: #000 !important;
  width: 54px;
  border: 1px solid #e5e5e5 !important;
  border-radius: 24px;
  text-align: center !important;
  max-height: 43px;
  margin: 0;
  font-size: 20px;
  font-weight: 500;
  padding: 0.25rem 0;
}
.container-add-cart .container-quantity .plus[data-v-435b3f04] {
  outline: 0;
  background: 0 0;
  border-radius: 50%;
  font-size: 18px;
  line-height: 1;
  width: 43px;
  height: 43px;
  border: 1px solid #e5e5e5;
  color: #fd4a1f;
}
.container-add-cart .add-to-cart[data-v-435b3f04] {
  color: #fff;
  border-width: 0 !important;
  border-radius: 24px;
  font-size: 16px;
  font-family: 'DM Sans';
  background-color: #239cd8 !important;
  padding: 8px 24px !important;
  text-transform: uppercase !important;
  width: 100%;
  font-weight: 700;
}
.product-price .add-wish[data-v-435b3f04] {
  color: #fd4a1f;
  border: 1px solid #e9e9e9;
  padding: 8px 16px;
  text-align: center;
  border-radius: 24px;
  display: block;
  font-weight: 500;
  outline: 0;
  width: 100%;
  margin-top: 1rem;
}
.quickpay-button[data-v-435b3f04] {
  width: 100%;
  border-radius: 35px !important;
  font-family: 'DM Sans' !important;
  font-weight: 700 !important;
  background: #fd4a1f !important;
  padding: 11px 24px !important;
  margin-bottom: 10px;
  text-transform: uppercase !important;
  color: #fff;
  display: inline-block;
  text-align: center;
  border: 0;
  letter-spacing: 0;
  outline: 0;
  height: 43px;
  box-shadow: 0 1px 2px 0 rgba(0, 0, 0, 0.2);
  transition: box-shadow 0.2s ease;
}
.quickpay-button[data-v-435b3f04]:hover {
  box-shadow: 0 4px 6px 0 rgba(0, 0, 0, 0.12);
}
.rappipay-button[data-v-435b3f04] {
  box-shadow: 0 1px 2px 0 rgba(0, 0, 0, 0.2);
  height: 43px;
  line-height: 1 !important;
  color: #fff;
  text-decoration: none;
  text-shadow: none;
  background: linear-gradient(
    140.58deg,
    #ff7d45 -1.15%,
    #ff0c37 29.37%,
    #ff0c37 62.21%,
    #ff3e8f 104.79%
  );
  border: none;
  border-radius: 35px;
  margin-bottom: 10px;
  margin-top: 10px;
  cursor: pointer;
  text-align: center;
  text-transform: uppercase;
  position: relative;
  display: inline-block;
  width: 100%;
  padding: 5px 10px;
  transition: box-shadow 0.2s ease;
}
.rappipay-button[data-v-435b3f04]:hover {
  box-shadow: 0 4px 6px 0 rgba(0, 0, 0, 0.12);
}
.rappipay-button img[data-v-435b3f04] {
  height: 30px;
  margin: auto;
}
.container-pay[data-v-435b3f04] {
  margin-bottom: 0.5rem;
}

.r-24[data-v-d7f86b2e] {
  border-radius: 24px;
}
</style>
