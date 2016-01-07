set hlsearch
set scrolloff=3
set ignorecase smartcase
set showmode
set history=1000

" easy system clipboard copy/paste
noremap <space>y "*y
noremap <space>Y "*Y
noremap <space>p "*p
noremap <space>P "*P

" easy window navigation
nnoremap <c-l> <c-w>l
nnoremap <c-j> <c-w>j
nnoremap <c-h> <c-w>h
nnoremap <c-k> <c-w>k
nnoremap <a-h> gT
nnoremap <a-l> gt
nnoremap <c-s-tab> gT
nnoremap <c-tab> gt

" clear the search buffer when hitting return
nnoremap <space><cr> :nohlsearch<cr>

" options
nnoremap cow :action EditorToggleUseSoftWraps<cr>
nnoremap col :action EditorToggleShowWhitespaces<cr>

" actions
nnoremap <space>q :action CloseContent<cr>
nnoremap <space>Q :action ReopenClosedTab<cr>
nnoremap <space>\ :action VimFilePrevious<cr>
nnoremap <space>e :action SearchEverywhere<cr>
nnoremap <space>E :action Switcher<cr>
nnoremap <space>t :action FileStructurePopup<cr>
nnoremap <space>T :action GotoSymbol<cr>
nnoremap <space>a :action GotoAction<cr>
nnoremap <space>b :action ToggleLineBreakpoint<cr>

" code navigation
nnoremap <space>] :action GotoImplementation<cr>
nnoremap <space>[ :action GotoSuperMethod<cr>
nnoremap <space>u :action FindUsages<cr>
nnoremap <space>gt :action GotoTest<cr>
nnoremap <space>k :action HighlightUsagesInFile<cr>
nnoremap \r :action RunClass<cr>
nnoremap \R :action Run<cr>
nnoremap \d :action DebugClass<cr>
nnoremap \D :action Debug<cr>
nnoremap \c :action CheckStyleCurrentFileAction<cr>

" code refactoring
nnoremap <space>rr :action RenameElement<cr>

" unimpaired mappings
nnoremap [<space> O<esc>j
nnoremap ]<space> o<esc>k
nnoremap [q :action PreviousOccurence<cr>
nnoremap ]q :action NextOccurence<cr>
nnoremap [m :action MethodUp<cr>
nnoremap ]m :action MethodDown<cr>
nnoremap [c :action VcsShowPrevChangeMarker<cr>
nnoremap ]c :action VcsShowNextChangeMarker<cr>


" built-in navigation to navigated items works better
nnoremap <c-o> :action Back<cr>
nnoremap <c-i> :action Forward<cr>
" but preserve ideavim defaults
nnoremap g<c-o> <c-o>
nnoremap g<c-i> <c-i>

" built in search looks better
nnoremap / :action Find<cr>
" but preserve ideavim search
nnoremap g/ /
