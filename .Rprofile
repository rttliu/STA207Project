local({
  if (nzchar(Sys.getenv("RSTUDIO_PANDOC"))) {
    return(invisible(NULL))
  }

  pandoc_dir <- "C:/Program Files/RStudio/resources/app/bin/quarto/bin/tools"

  if (dir.exists(pandoc_dir)) {
    Sys.setenv(RSTUDIO_PANDOC = normalizePath(pandoc_dir, winslash = "/", mustWork = TRUE))
  }
})
